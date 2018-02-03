# JDK 8 images
FROM shinley/centos:ssh
MAINTAINER chenxinlei "cxl17258@qq.com"
ADD ./jdk-8u161-linux-x64.tar.gz /usr/local/
ENV JAVA_HOME=/usr/local/jdk1.8.0_161
ENV JRE_HOME $JAVA_HOME/jre
ENV PATH=$PATH:$JAVA_HOME/bin
ENV CLASSPATH=.:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar
EXPOSE 22
