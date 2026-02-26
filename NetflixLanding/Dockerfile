FROM nginx:alpine

# Serve the landing page as a static site.
COPY landingindex.html /usr/share/nginx/html/index.html
COPY landingstyle.css /usr/share/nginx/html/landingstyle.css
COPY landingscript.js /usr/share/nginx/html/landingscript.js
COPY assets /usr/share/nginx/html/assets
EXPOSE 80
