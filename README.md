# Spring Boot starter

A minimal [Spring Boot](https://spring.io/projects/spring-boot) web app in Java 21, built with the Maven wrapper.

## Run it locally

```sh
./mvnw spring-boot:run
```

Then open http://localhost:8080. `GET /health` answers `ok` for health checks.

## Deploying

| Step | Command |
| --- | --- |
| Build | ./mvnw -DskipTests package |
| Start | java -jar target/app.jar |

## Environment variables

| Variable | Meaning |
| --- | --- |
| `PORT` | Port to listen on. Default: 8080. |

## License

MIT
