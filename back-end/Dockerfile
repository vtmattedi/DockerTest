FROM node

WORKDIR /src/usr/

COPY . .

EXPOSE 4500

RUN npm i
RUN npm run build

CMD ["npm", "start"]