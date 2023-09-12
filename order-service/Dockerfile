# base image
FROM amazoncorretto:11-alpine-jdk

COPY ./build/libs/order-service-0.0.1-SNAPSHOT.jar .

CMD ["java", "-jar", "./order-service-0.0.1-SNAPSHOT.jar"]