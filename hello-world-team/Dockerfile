FROM openjdk:8-jdk-alpine
EXPOSE 8080
ADD target/hello-world-team.jar hello-world-team.jar
ENTRYPOINT ["sh", "-c", "java -jar /hello-world-team.jar"]