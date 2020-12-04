# spring-boot-microservices
Spring Boot Microservices

# How to create new spring boot project

	1. Open Spring Tool Suite
	2. Go to File -> New -> Spring Starter Project -> Service URL
		
		Service URL: https://start.spring.io
		
# New Spring Starter Project attributes
	  The following attributes are supported:
        
        Spring Boot version: platformVersion
        Dependencies: dependencies
        Programming language: language (java, groovy or kotlin)
        Java version: javaVersion (1.8, 11, 12)
        Project type: type (maven-project, gradle-project)
        Packaging: packaging (jar, war)
        Group: groupId
        Artifact: artifactId
        Name: name
        Description: description
        Package Name: packageName
	
	1. Name: display name of the project that also determines the name of your Spring Boot application. For instance, if the name of your project is my-app, the generated project will have a MyAppApplication class
		
	2. Type: Maven
	
	3. Packaging: project packaging (as referred by the concept of the same name in Apache Maven). start.spring.io can generate jar or war projects
	
	4. Java Version: 8
	
	5. Language: Java/Kotlin/Groovy
	
	6. Group: project coordinates (id of the project’s group, as referred by the groupId attribute in Apache Maven). Also infers the root package name to use.
	
	7. Artifact: project coordinates (id of the artifact, as referred by the artifactId attribute in Apache Maven). Also infers the name of the project
	
	8. Version: project version
	
	9. Description: description of the project
	
	10. Package: root package of the project. If not specified, the value of the Group attribute is used
