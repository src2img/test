FROM node:14

COPY . /app
WORKDIR /app

RUN \
  npm install && \
  npm run print-http-server-version

EXPOSE 8080

CMD ["npm", "start"]