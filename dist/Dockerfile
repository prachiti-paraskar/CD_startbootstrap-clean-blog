# Use an official NGINX runtime as a parent image
FROM nginx:stable-alpine

# Copy the static website's content from the current directory to the NGINX HTML directory
COPY . /usr/share/nginx/html

# Expose port 80 to allow traffic to the web server
EXPOSE 80

# The command to start NGINX when the container launches
CMD ["nginx", "-g", "daemon off;"]
