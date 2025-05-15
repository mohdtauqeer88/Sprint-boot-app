# Spring Boot Application

This is a simple Spring Boot application that demonstrates the basic structure and functionality of a Spring Boot project.

## Project Structure

```
spring-boot-app
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── example
│   │   │           └── springbootapp
│   │   │               ├── SpringBootAppApplication.java
│   │   │               └── controller
│   │   │                   └── HelloController.java
│   │   └── resources
│   │       ├── application.properties
│   │       └── static
│   │           └── index.html
│   └── test
│       └── java
│           └── com
│               └── example
│                   └── springbootapp
│                       └── SpringBootAppApplicationTests.java
├── pom.xml
└── README.md
```

## Prerequisites

- Java 11 or higher
- Maven

## Build and Run

1. Clone the repository:
   ```
   git clone <repository-url>
   cd spring-boot-app
   ```

2. Build the application using Maven:
   ```
   mvn clean install
   ```

3. Run the application:
   ```
   mvn spring-boot:run
   ```

4. Access the application in your web browser at:
   ```
   http://localhost:8080/hello
   ```

## Endpoints

- **GET /hello**: Returns a greeting message.

## Testing

To run the tests, use the following command:
```
mvn test
```

## License

This project is licensed under the MIT License.