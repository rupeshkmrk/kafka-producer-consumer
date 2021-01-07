## Spring Boot with Kafka Producer Example

### Below are the command for Linux/Mac and Windows

## Start Zookeeper
- `bin/zookeeper-server-start.sh config/zookeeper.properties`
- `.\bin\windows\zookeeper-server-start.bat config\zookeeper.properties`

## Start Kafka Server
- `bin/kafka-server-start.sh config/server.properties`
- `.\bin\windows\kafka-server-start.bat config\server.properties`

## Create Kafka Topic
- `bin/kafka-topics.sh --create --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --topic Kafka_Example`
- `.\bin\windows\kafka-topics.bat --create --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --topic NewTopic`
