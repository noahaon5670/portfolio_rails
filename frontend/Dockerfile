FROM node:16

WORKDIR /app

ENV LANG C.UTF-8
ENV TZ Asia/Tokyo

RUN apt-get update -y && \
  apt-get upgrade -y && \
  npm install npm@8.1.3 && \
  npm install ejs@3.1.6 && \
  npm install nuxt@2.15.8 && \
  npm install create-nuxt-app@3.7.1 && \
  npm install defu@5.0.0
  
ADD . /app
