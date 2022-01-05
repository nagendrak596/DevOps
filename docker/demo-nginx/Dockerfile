FROM ubuntu:18.04
MAINTAINER nagendra <nagendrak.596@gmail.com>
RUN apt-get update
RUN apt-get install git maven wget nginx -y
COPY index.nginx-debian.html  /var/www/html/
RUN service nginx restart
EXPOSE 80 
