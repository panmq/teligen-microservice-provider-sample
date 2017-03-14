FROM frolvlad/alpine-oraclejdk8:slim
VOLUME /tmp
ADD teligen-microservice-provider-sample.jar teligen-microservice-provider-sample.jar
RUN sh -c 'touch /teligen-microservice-provider-sample.jar'
ENV JAVA_OPTS=""
ENTRYPOINT ["sh", "-c", "java $JAVA_OPTS -jar /teligen-microservice-provider-sample.jar"]