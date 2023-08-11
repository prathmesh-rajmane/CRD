# Creating Kubernetes Custom Resource Definition and Controller

This repo contains code about how you can create a kubernetes CRD and also a controller that
will handle requests when a custom resource instance is created or deleted. 

Steps:

run model script.
#use docker system prune if required.
copy files from /tmp/java/..../models/*.java to your local code path

go to crd path & run
k apply -f my-crd.yaml
k apply -f my-resource-instance.yaml

go to code path & run 
mvn spring-boot:run


