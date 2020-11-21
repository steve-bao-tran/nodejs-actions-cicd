# image base, nodejs version latest
FROM node:13-alpine

# mkdir /app && cd /app
WORKDIR /app

# cp . . <=> cp docker-node/ .
COPY . .

# Command npm install packages dependencies
RUN npm install

# Run app
CMD ["npm", "start"]