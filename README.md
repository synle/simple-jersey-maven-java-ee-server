maven-jersey-java-ee-webapp
===========================

Source: https://jersey.java.net/documentation/latest/getting-started.html

To install and package
```
mvn clean package

#war is store in
./target/simple-service-webapp.war./target/simple-service-webapp.war
```

Sample URL for Server
```
http://localhost:8084/maven-sample-java-ee-project/webapi/myresource
```

To generate the project from scratch
```
mvn archetype:generate -DarchetypeArtifactId=jersey-quickstart-webapp \
  -DarchetypeGroupId=org.glassfish.jersey.archetypes -DinteractiveMode=false \
  -DgroupId=com.example -DartifactId=simple-service-webapp -Dpackage=com.example \
  -DarchetypeVersion=2.25.1
```

