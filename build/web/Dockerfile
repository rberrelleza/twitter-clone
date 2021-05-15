FROM node:lts-alpine

WORKDIR /usr/src/web

COPY package.json .
COPY yarn.lock .

RUN yarn install

EXPOSE 3000

CMD ["tail", "-f", "/dev/null"]