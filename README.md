# Java 4 Docker: Java Gradle "Hello World"

This project is my attempt at following the
["Building Java Projects with Gradle"](https://spring.io/guides/gs/gradle/#scratch)
guide at [spring.io](https://spring.io), but this time using Docker exclusively
for the development process :)

## Prerequisites

1. Have Docker & Docker Compose Installed
2. Clone the project
3. Move to the cloned project's folder

OH MY: This project uses the Oracle Java Server JRE, which requires you to
have a Docker account (which is free) and accept the Licence Agreement at [Oracle Java Server JRE Image](https://hub.docker.com/_/oracle-serverjre-8) (The "Proceed to Checkout" button over there - it's also free)

4. Ensuse your authenticated your docker CLI: `docker login`

## Run Demo

```
docker-compose run hello_world
```
