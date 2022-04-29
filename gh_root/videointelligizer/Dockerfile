FROM nginx:latest

LABEL Name=video-intelligizer Version=0.0.1

RUN apt update && apt upgrade -y
RUN apt install git -y

WORKDIR /usr/share/nginx
COPY ./ /usr/share/nginx/html/