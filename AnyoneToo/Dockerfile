FROM openjdk:17

LABEL version=0.1

ARG JAR_NAME=AnyoneToo-0.0.1-SNAPSHOT.jar

ARG JAR_PATH=./build/libs/${JAR_NAME}

RUN mkdir -p /app

WORKDIR /app

COPY ${JAR_PATH} /app/app.jar

CMD ["java", "-jar", "/app/app.jar"]