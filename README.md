# rest-api
REST API template application

## About The Project

This is template project for building REST API application using Java and Spring Boot.

### Built With

* [Java 21](https://www.oracle.com/java/technologies/downloads/#java21)
* [Apache Maven](https://maven.apache.org/guides/index.html)
* [Cloud Native Buildpacks](https://docs.spring.io/spring-boot/3.5.8/maven-plugin/build-image.html)
* [Spring Boot Testcontainers support](https://docs.spring.io/spring-boot/3.5.8/reference/testing/testcontainers.html#testing.testcontainers)
* [Testcontainers Postgres Module Reference Guide](https://java.testcontainers.org/modules/databases/postgres/)
* [Spring Configuration Processor](https://docs.spring.io/spring-boot/3.5.8/specification/configuration-metadata/annotation-processor.html)
* [Spring Web](https://docs.spring.io/spring-boot/3.5.8/reference/web/servlet.html)
* [Spring Security](https://docs.spring.io/spring-boot/3.5.8/reference/web/spring-security.html)
* [Spring Data JPA](https://docs.spring.io/spring-boot/3.5.8/reference/data/sql.html#data.sql.jpa-and-spring-data)
* [Spring Boot Actuator](https://docs.spring.io/spring-boot/3.5.8/reference/actuator/index.html)
* [Docker Compose Support](https://docs.spring.io/spring-boot/3.5.8/reference/features/dev-services.html#features.dev-services.docker-compose)
* [Testcontainers](https://java.testcontainers.org/)

## Getting Started

### Prerequisites

1. Install Java 21. We recommend to use [sdkman](https://sdkman.io/).

### Running locally

1. Open a terminal and change directory to the project.
2. Run using maven wrapper
   ```sh
   ./mvnw spring-boot:run
   ```
3. Verify the application is running by opening a browser or via Postman.
   - Go to [http://localhost:8080/actuator/health](http://localhost:8080/actuator/health) and response should be `UP`.

## Usage


## License

See `LICENSE` for more information.

## Contact


## Acknowledgments

* [Spring Initializr](https://start.spring.io/)