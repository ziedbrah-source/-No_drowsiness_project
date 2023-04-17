# No Drowsiness in Roads

"No Drowsiness in Roads" is a mobile application that helps prevent drowsy driving accidents by using advanced technology to detect when a driver is getting drowsy and alerting trusted contacts.

## Features

- Uses computer vision and AI technology to detect when a driver is becoming drowsy or falling asleep.
- Sends the driver's location information to the backend through RabbitMQ, a reliable message broker.
- Alerts trusted contacts with a notification if the driver needs assistance.
- Easy-to-use mobile application built with React Native.

## Installation
### Let's start with the backend :
- go to the backend folder.
- To install the project dependencies, run the following command:
```node
npm install
```
- You need also to install mysql (check this if you are on ubuntu : [Ubuntu mysql](https://ubuntu.com/server/docs/databases-mysql).) .
- Now you need to run the backend server, run the following command: 
```node
npm start
```
- now the backend is ready.
### Let's run the script for the camera
- Go to Ai_part folder.
- Run DrwsinessMonitorProject.ipynb and enter your icloud information.
### Now we will go to the frontend.
- Go to the frontend folder.
- To install the project dependencies, run the following command:
```node
npm install
``` 
- You need also to install Expo Cli :  [Expo Docs](https://docs.expo.dev/get-started/installation/)
- Now you need to start the frontend server using
```node
npm start
``` 
-Scan the Qrcode with your phone camera and you will be linked to the mobile application ready to go .


## Technologies Used

- React Native
- NestJS
- MySQL
- RabbitMQ
- iCloud API
- OpenCV
## Architecture 

[![Screenshot-from-2023-04-16-20-14-36.png](https://i.postimg.cc/DzrMCTSz/Screenshot-from-2023-04-16-20-14-36.png)](https://postimg.cc/06NnQhdg)


## Why we used RabbitMQ here

- Message queueing: RabbitMQ is a message broker that allows your application to send and receive messages asynchronously. This can help to decouple your application components and make them more scalable.
- Durability: RabbitMQ is designed to ensure that messages are not lost, even if the application or backend goes down. This is achieved through the use of message queues, which store messages until they are processed.
- Fault-tolerance: RabbitMQ is designed to be highly available and fault-tolerant. It provides features such as clustering and replication to ensure that your messages are always available, even if a server fails.
- Scalability: RabbitMQ can handle large volumes of messages and can scale horizontally by adding more servers to the cluster.
- Reliability: RabbitMQ guarantees that messages will be delivered to their intended recipients, even if there are network issues or other failures.
- Overall, RabbitMQ provides a reliable, scalable, and fault-tolerant messaging solution for your project. By using RabbitMQ, you can ensure that messages are not lost and that your application remains responsive, even in the face of failures.

## Contributing

Contributions to the project are always welcome. If you'd like to contribute, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

If you have any questions or comments about the project, please feel free to reach out to us at [LinkedIn](https://www.linkedin.com/in/mohamed-zied-brahmi/)
