# ums-registry

# Deployment Server
 - IP - 139.84.167.86
 - Port - 8761

# Architecture
 - Java version - 1.8
 - Maven version - apache-maven-3.8.2

# Jar file location 
- ums-registry/target/Registry.jar

# Log file path
 - /home/core/registry/nohup.out

# Properties file path
 - /home/core/ums/registry/application.properties

# Command to build the project
mvn clean install

# Command to run the project
Find the script file to start, stop and check the status of the application.
/home/core/scripts
 - start.sh
 - stop.sh
 - status.sh

The start.sh runs the registry and gateway

The stop.sh stops the registry and gateway 

The status.sh checks the status of the registry and gateway application

Please execute this once for both the applications (registry & gateway) to run.