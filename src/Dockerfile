# Use a imagem base do Ubuntu
FROM node:20.9.0-alpine3.18

WORKDIR /app
COPY . .

# Instale as dependências da aplicação 
RUN npm install 

EXPOSE 8080

# Comando para iniciar a aplicação
ENTRYPOINT [ "node","server.js"