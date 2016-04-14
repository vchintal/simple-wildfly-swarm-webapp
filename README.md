## Simple Wildfly Swarm Webapp

Simple servlet based webapp to demostrate how Wildfly Swarm works and automatically resolves the _fractions_ needed to deploy and run the webapp in Wildfly container.

Run the following command to test the project:

```sh 
mvn clean package wildfly-swarm:run

# In a seperate terminal test the following command
curl http://127.0.0.1:8080/HelloWorld
```


