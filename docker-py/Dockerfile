FROM ubuntu:16.04
MAINTAINER Rafal Leszko
ENV NAME Rafal
RUN apt-get update && \
    apt-get install -y python
COPY hello.py .
ENTRYPOINT ["python", "hello.py"]