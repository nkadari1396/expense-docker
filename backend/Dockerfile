FROM node:20
EXPOS 8080
ENV DB_HOST="mysql"
RUN  mkdir /opt/server
WORKDIR /opt/server
COPY package.json .
COPY *.js .
RUN npm install
CMD ["node", index.js]