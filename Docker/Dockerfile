FROM eaps-docker-coldfusion.bintray.io/cf/coldfusion:latest

MAINTAINER Oguzhan Igrek <oguzhanigrek@gmail.com>

LABEL Name=oguzhanigrekcoldfusion Version=0.0.1

RUN apt-get -y update && apt-get install -y git && apt-get install ca-certificates

ENV acceptEULA=YES

ENV password=ColdFusion123

WORKDIR /home/w3/Desktop/ColdfusionDocker

CMD git clone https://github.com/oguzhanigrekk/coldfusionDocker.git

EXPOSE 8500
