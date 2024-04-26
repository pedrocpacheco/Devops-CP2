FROM node:lts-alpine3.19

USER node

WORKDIR /app-money

RUN mkdir -p /app-money && chown -R node:node /app-money

COPY . .

RUN npm install

EXPOSE 3000

CMD ["node", "index.js"]
