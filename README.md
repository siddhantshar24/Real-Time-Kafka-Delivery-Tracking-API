# Real-Time-Kafka-Delivery-Tracking-API
A delivery application which uses the Kafka pub/sub model of sending messages.

REST API Project for building a delivery pub/sub model in which the delivery boy acts as a Producer and the user recieving the delivery acts as a consumer.

Technologies used: Java, SpringBoot, REST API, Kafka, Zookeeper.

Description about technologies used:

The application uses the Producer and sends the location in the form of X-Y coordinates to the user/consumer.

The application aims at improving the transfer of information by sending data in the form of streams of messages.

The location is updated every second and the user is able to get an idea about the delivery boy's real-time location.

To start the project in your local:

-Start Kafka, Zookeeper, and create Producer and Consumer in command prompt using scripts mentioned in https://github.com/siddhantshar24/Kafka-cmd-scripts files.

-Go to main folder in Intellij/Eclipse and run both the consumer and producer applications as a SpringBoot Application

-The values of location would be recieved respectfully in the consumer terminal window.

-Make sure your Kafka is setup and running before starting the application.

Thanks.
