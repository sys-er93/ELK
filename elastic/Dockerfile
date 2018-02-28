FROM elasticsearch
MAINTAINER edu <eduardo.romero@babel.es>
RUN apt-get update -y
RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install x-pack --batch
#ADD ./archivos /archivos
#WORKDIR /archivos
#COPY hello.sh /archivos
#EXPOSE 5000 80 22
