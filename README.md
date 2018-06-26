# Activiti Cloud Gateway
This project is using the Spring Cloud Gateway project along the Spring Cloud Kubernetes project to create dynamic routes
to the services registered inside a Kubernetes namespace. 

The main goal of this project is to provide a single entrypoint for your client applications to interact with a set of backend services.

Currently spring.cloud.gateway classes are overridden in the project due to these issues:

https://github.com/spring-cloud/spring-cloud-gateway/issues/229
and
https://github.com/spring-cloud/spring-cloud-gateway/issues/314