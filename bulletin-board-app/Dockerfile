FROM node:current-slim

WORKDIR /usr/src/app
COPY package.json .
RUN npm install

EXPOSE 8083
CMD [ "npm", "start" ]

COPY . .
