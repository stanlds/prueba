FROM node:16-alpine3.11

WORKDIR /mercado-libre-api
COPY . .
RUN yarn install --production

CMD ["node", "mercado-libre-api/src/index.js"]
