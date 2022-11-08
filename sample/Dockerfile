FROM node:18.12.0-alpine3.15

WORKDIR /opt/app

COPY package.json ./
 
COPY package-lock.json ./
 
RUN npm install
 
COPY . .
 
EXPOSE 3000
 
CMD ["npm", "start"]

