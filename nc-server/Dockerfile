FROM busybox:1

WORKDIR /www
COPY index.html /www/index.html

EXPOSE 8080

CMD ["nc", "-l", "-p", "8080", "-e", "cat", "index.html"]
