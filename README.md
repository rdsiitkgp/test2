# Document Storage REST Web Service

### Running as Spring-Boot Standalone Application 
##### Build
```
$ cd CognizantAssignment/
$ mvn clean package
```
##### Deploy
```
$ java -jar target/Assignment-1.0-SNAPSHOT.war
```
##### Endpoint
```
$ wget http://localhost:8080/storage/documents/74b985ad6da241a9bbd0
```

### Deploying war file in Tomcat
##### Build
```
$ cd CognizantAssignment/
$ mvn clean package
```
##### Deploy
```
$ sudo cp target/Assignment-1.0-SNAPSHOT.war /Library/Tomcat/webapps/
$ /Library/Tomcat/bin/startup.sh
```
##### Endpoint
```
$ http://localhost:8080/Assignment-1.0-SNAPSHOT/storage/documents/74b985ad6da241a9bbd0
```
