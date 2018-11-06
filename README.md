# appengine-standard-datastore-springboot-sample

This project is a Working example of appengine standard datastore springboot application, It refers official [spring-cloud/spring-cloud-gcp](https://github.com/spring-cloud/spring-cloud-gcp) for most of it's implementation.

# Getting Started
Update application.properties file 

```
spring.cloud.gcp.project-id=[YOUR_GCP_PROJECT_ID]
spring.cloud.gcp.credentials.location=file:[LOCAL_PRIVATE_KEY_FILE]
spring.cloud.gcp.credentials.scopes=[SCOPE_1],[SCOPE_2],[SCOPE_3]
```

Use `mvn appengine:run` to run this app locally.
Use `mvn appengine:deploy` to deploy this app to appengine.

# Additional Info
Refer [spring-cloud/spring-cloud-gcp](https://github.com/spring-cloud/spring-cloud-gcp) for more clarification.
