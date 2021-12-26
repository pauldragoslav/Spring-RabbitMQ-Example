# Spring-boot RabbitMQ
Example project demonstrating the use of RabbitMQ with Spring-boot

## Set up RabbitMQ broker using Docker
```
docker-compose up
```

## Update Configuration
Set the value of _spring.rabbitmq.host_ to the ip of RabbitMQ Docker container

## Run the Application
```
./mvnw clean package
java -jar target/rabbitmq-0.0.1.jar
```

### Source and Resources
* https://spring.io/guides/gs/messaging-rabbitmq/
* https://github.com/spring-guides/gs-messaging-rabbitmq
* https://docs.spring.io/spring-amqp/reference/html/
* https://spring.io/blog/2010/06/14/understanding-amqp-the-protocol-used-by-rabbitmq
