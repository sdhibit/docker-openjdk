FROM sdhibit/alpine-runit:3.6
MAINTAINER Steve Hibit <sdhibit@gmail.com>

# Install apk packages
RUN apk --update upgrade \
 && apk add \
  openjdk8-jre \
 && rm /var/cache/apk/*

ENV JAVA_HOME /usr/lib/jvm/java-1.8-openjdk
ENV PATH $PATH:/usr/lib/jvm/java-1.8-openjdk/jre/bin:/usr/lib/jvm/java-1.8-openjdk/bin
