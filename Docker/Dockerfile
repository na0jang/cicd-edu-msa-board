FROM tomcat:9-jre8-alpine
WORKDIR /usr/local/tomcat
COPY ./Docker/server.xml ./conf
RUN rm -rf ./webapps/*
COPY ./edu-msa-board/target/edu-msa-board-1.0.0.war ./webapps/edu-msa-board-1.0.0.war

EXPOSE 28082
