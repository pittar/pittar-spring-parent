# Sample Parent POM

Instead of using the Spring Boot parent directly, it can be useful to leverage your own parent pom that includes the build plugins specific to your project.

Maintaining your own parent pom can also reduce copy/paste between your applications, as all of your Spring apps should use the same common parent pom (although possibly different versions).