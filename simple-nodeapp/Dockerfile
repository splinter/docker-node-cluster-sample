FROM node:0.10

WORKDIR /src
ADD /src /src

RUN npm install -g nodemon

EXPOSE 8000

CMD ["nodemon","/src/app.js"]

