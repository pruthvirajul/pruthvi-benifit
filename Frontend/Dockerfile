# Use Nginx for serving static files
FROM nginx:alpine

# Remove default nginx index
RUN rm -rf /usr/share/nginx/html/*

# Copy static files to nginx public directory
COPY . /usr/share/nginx/html

# Expose nginx port
EXPOSE 80

