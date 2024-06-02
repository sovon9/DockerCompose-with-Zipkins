# DockerCompose-with-Zipkins
currency microservice using docker compose file and zipkin's full tracing

make sure your artifact id name is in small case otherwise there will be image building issue
*	now got to Maven Build > then in goal put: spring-boot:build-image -DskipTests
*	do git push (image-name) <= if you want to push local image to dockerhub
*	run docker-compose up
