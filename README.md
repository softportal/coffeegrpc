# coffeegrpc
A example of a gRPC service of a coffee machine inspired in the hello world example from google
# build & run on localhost
```bash
mvn clean package
mvn exec:java -Dexec.mainClass=iotucm.coffeeservice.CoffeeServiceServer
mvn exec:java -Dexec.mainClass=iotucm.coffeeservice.CoffeeServerClient -Dexec.args="client1 volluto"
```
# build & run remotely
[conf_coffee_gRPC](https://github.com/pilotAlpal/conf_coffee_gRPC/blob/master/README.md#conf_coffee_grpc)
