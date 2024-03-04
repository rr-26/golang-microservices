# Highly available, scalable, resilient, distributed application using Go

## Description
In this Project, I developed a microservice architecture in Golang. The application has the following features:

- It emphasizes maintainability and testability;
- It promotes loose coupling with other parts of the application;
- It enables independent deployment;
- It is structured around business capabilities;
- It is typically managed by a small team.

The self-contained, loosely coupled microservices will communicate with one another and a simple front-end application with a REST API, with RPC, over gRPC, and by sending and consuming messages using AMQP, the Advanced Message Queuing Protocol. The microservices we build will include the following functionality:

1. **Front End service**: It just displays web pages.
2. **Authentication service**: Handles authentication with a Postgres database.
3. **Logging service**: Manages logging with a MongoDB database.
4. **Listener service**: Receives messages from RabbitMQ and acts upon them.
5. **Broker service**: An optional single point of entry into the microservice cluster.
6. **Mail service**: Takes a JSON payload, converts into a formatted email, and sends it out.

All of these services are written in Go, particularly well suited to building distributed web applications.


## Resources
- [Go Documentation](https://golang.org/doc/)
- [Docker Documentation](https://docs.docker.com/)
- [Kubernetes Documentation](https://kubernetes.io/docs/)
- [RabbitMQ Documentation](https://www.rabbitmq.com/documentation.html)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
