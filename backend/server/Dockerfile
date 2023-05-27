FROM node:14-alpine

WORKDIR /app

COPY package*.json ./
RUN npm ci --only=production

COPY ../../package*.json ./

CMD [ "node", "server.js" ]
