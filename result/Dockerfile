FROM node:12-alpine
ENV NODE_VERSION 12.18.4
WORKDIR /app
COPY . /app
RUN npm install
EXPOSE 80
CMD ["node", "server.js"]
