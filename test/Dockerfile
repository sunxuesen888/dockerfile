FROM busybox:latest
MAINTAINER SXS
COPY index.html /data/web/html/
COPY apt /etc/yum.repos.d/
#ADD http://nginx.org/download/nginx-1.15.8.tar.gz /usr/local/src/
WORKDIR /usr/local/
ADD nginx-1.15.8.tar.gz /usr/local/src
VOLUME /data/mysql
