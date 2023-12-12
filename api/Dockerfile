FROM node:alpine
WORKDIR /time-app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 5555
CMD ["npm", "run", "dev"]