FROM nacos/nacos-server:1.1.4

WORKDIR /$BASE_DIR

RUN rm -f conf/application.properties
RUN rm -f target/nacos-server.jar

ADD conf/application.properties conf/application.properties
ADD target/nacos-server.jar target/nacos-server.jar
