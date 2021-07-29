## Theia IDE docker file for Spring Boot development

### First build the docker image
``docker build -t ygunduz/theia-spring-boot:latest .``

### Then run the application
``docker run -d -p 3000:3000 -v "$(pwd):/home/project:cached" ygunduz/theia-spring-boot:latest``

then locate the url [http://localhost:3000](http://localhost:3000) and start development.
