## Images Commands

docker images

docker image ls

docker pull <image-name>

docker rmi <image-id>

docker build 


## Container Commands

docker ps     (list all running container)

docker ps -a  (list all running/stooped containers)

docker ps -aq  (List only ID)

docker rm <cont-id>

docker rm -f $(docker ps -aq)

docker run

	docker run -it <image-name> /bin/bash
 
	docker exec -it <cont-id> /bin/bash

docker stop <cont-id/name>

docker start <cont-id/name>


# Install Jenkins

## Download JDK 17

https://download.oracle.com/java/17/archive/jdk-17.0.12_windows-x64_bin.msi

## Downlaod Jenkins

https://www.jenkins.io/download/thank-you-downloading-windows-installer-stable

## Jenkins Pipeline Plugin

1. Pipeline
2. Pipeline: Stage View
3. Pipeline: Build Steps
4. Pipeline: Basic Steps

# EKS Kubernetes Commands

aws eks --region ap-south-1 describe-cluster --name hiteshCluster --query cluster.status

aws eks --region ap-south-1 update-kubeconfig --name hiteshCluster

kubectl get pods -o wide
