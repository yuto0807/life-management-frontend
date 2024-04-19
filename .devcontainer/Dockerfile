FROM node:18.17-bullseye-slim as build

WORKDIR /usr/src/app

COPY ./ /usr/src/app

RUN npm install create-vite
# RUN npm run build
# RUN npm ci --only=production