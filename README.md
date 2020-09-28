# Spring Boot Azure AD Integration Example

This is a simple example that shows how to integrate Spring Boot with Azure AD based on this example: https://github.com/Azure/azure-sdk-for-java/tree/master/sdk/spring/azure-spring-boot-samples/azure-spring-boot-sample-active-directory-backend


## Getting started

You will need to register an application Azure AD to be able to configuration this example.
Follow this guide to do this: https://docs.microsoft.com/de-de/azure/developer/java/spring-framework/configure-spring-boot-starter-java-app-with-azure-active-directory

After that, copy `tenant-it`, `client-id`, `secret` and `groups` to the `application.properties`.

Then start the application and open this url in your browser:
```http://localhost:8080/login``` 
