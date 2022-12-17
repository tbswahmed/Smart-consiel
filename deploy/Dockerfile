FROM debian:latest
RUN apt-get update -y && apt install -y python3 python3-pip && apt install -y python
RUN mkdir /data
RUN apt-get install -y systemctl
COPY ~/Test/deploy/ /data
WORKDIR /data
