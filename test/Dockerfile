FROM node: latest

MAINTAINER Vikarsh

ENV NODE_ENV=development
ENV PORT=3000

COPY  ./var/www
WORKDIR /var/www

VOLUME ["var/www"]
RUN npm install

EXPOSE $PORT

ENTRYPOINT ["npm" , "start"]