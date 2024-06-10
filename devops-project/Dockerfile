FROM alpine:3.19

WORKDIR /app

COPY ./package*.json /app a /

RUN npm install

COPY . .

EXPOSE 5173

CMD ["npm", "run", "dev"]
