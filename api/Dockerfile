FROM node:20-alpine
WORKDIR /app
COPY server.js ./
COPY data ./data
COPY images ./images
EXPOSE 3333
CMD ["node", "server.js"]
