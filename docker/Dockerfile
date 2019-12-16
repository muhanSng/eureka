FROM java:8u111

VOLUME /tmp

ADD *.jar eureka.jar

EXPOSE 8761

ENTRYPOINT ["java","-jar","/eureka.jar"]

# 时区
RUN cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime