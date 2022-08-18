FROM node

WORKDIR /app

COPY . /app

RUN npm install

# expose local port when running container
EXPOSE 80

# will execute when a container based on the image
# is initialized, not when the image is created
CMD ["node", "server.js"]