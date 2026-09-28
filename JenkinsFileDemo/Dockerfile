FROM node:22

WORKDIR /app

COPY package*.json ./

RUN npm install 

COPY server.json .

EXPOSE 3000

CMD ["npm","start"]