FROM java:8
EXPOSE 8080
ADD /spring-hello.war spring-docker.war
ENTRYPOINT ["java","-jar","spring-docker.war"]