FROM openjdk:11-jdk-alpine
RUN mkdir /app
WORKDIR /app
COPY docker-demo/0.0.1-SNAPSHOT/docker-demo-0.0.1-SNAPSHOT.jar /app
EXPOSE 8081
ENTRYPOINT ["java", "-jar", "/docker-demo-0.0.1-SNAPSHOT.jar"]