FROM node:14-alpine
WORKDIR /backend
ADD node_modules.tar.gz .
EXPOSE 3001
COPY . .
ENTRYPOINT ["npm", "start"]
