FROM mhart/alpine-node:8.16.0
RUN apk update
RUN apk upgrade
RUN apk add --no-cache ca-certificates
RUN apk add --no-cache bash
RUN apk add --no-cache git
RUN apk add --no-cache openssh
RUN rm -rf /var/cache/apk/*
