FROM node:14-alpine
WORKDIR /opt/app
ADD *.json .
ADD . .
RUN npm install
RUN npm run build api
CMD ["node", "./dist/apps/api/main.js"]