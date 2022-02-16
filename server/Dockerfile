FROM node:14

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 4000

RUN npm run build

RUN npm start

# CMD ["npm", "start" ]
