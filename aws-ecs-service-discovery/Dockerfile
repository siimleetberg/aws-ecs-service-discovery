FROM python:2.7

MAINTAINER Bruno Bronosky <richard@bronosky.com>

WORKDIR /app

RUN pip install -U git+https://github.com/RichardBronosky/aws-ecs-service-discovery.git

ENTRYPOINT ["awsesd"]
