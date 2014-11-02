FROM ubuntu:trusty

ADD sources.list /etc/apt/

RUN \
	apt-get update && \
	apt-get install -y openjdk-7-jdk && \
	apt-get install -y maven && \
	rm -rf /var/lib/apt/lists/*

