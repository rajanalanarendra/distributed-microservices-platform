# Use official Node.js image
FROM node:16

# Set working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy the rest of the source code
COPY . .

# Expose the service port (adjust if needed)
EXPOSE 5003

# Start the service
CMD ["npm", "start"]
