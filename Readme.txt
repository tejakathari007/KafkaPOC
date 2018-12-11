Spring_Boot_Kafka :

   This is the POC on kafka where I have sent "Employee name, Department and Salary" from producer to consumer i.e., from one micro service to other.

Pre-Requisites(windows) :

Start Zookeeper -
from C:\kafka_2.12-2.1.0\kafka_2.12-2.1.0
.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties

Start Kafka in windows -
from C:\kafka_2.12-2.1.0\kafka_2.12-2.1.0
.\bin\windows\kafka-server-start.bat .\config\server.properties

