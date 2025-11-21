# use existing base image
FROM node:14-alpine

WORKDIR /usr/app

# Install all dependencies
COPY ./ ./
RUN npm install

# Default Command
CMD ["npm","start"]