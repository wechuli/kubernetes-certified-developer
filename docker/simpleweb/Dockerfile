#specify a base image
FROM node:alpine

#specify the working directory

WORKDIR /usr/app

#Copy files

COPY ./package.json ./

#install some dependencies
RUN npm install
COPY ./ ./   
#to present unnecessary builds
#Defult command

CMD ["npm","start"]

