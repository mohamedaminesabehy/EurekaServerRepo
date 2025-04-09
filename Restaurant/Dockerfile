FROM openjdk:17-jdk-slim
WORKDIR /app
COPY target/Restaurant-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 9096
ENTRYPOINT ["java", "-jar", "app.jar"]