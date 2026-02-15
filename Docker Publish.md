# Steps to create and publish Docker image to DockerHub

Steps and commands as follows

mvnw clean package --> at source directory of Spring Project

docker build -t springai_ollama . -->

docker login

docker images

docker tag springai_ollama sarva123/springai_ollama:latest

docker push sarva123/springai_ollama:latest
