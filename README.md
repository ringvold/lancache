Docker compose for lancachenet LAN cache
=========================================

Docker compose setup for running https://lancache.net/ LAN cache containers.

Requires this command to be run before starting containers: 
```
export HOST_IP=`hostname -I | cut -d' ' -f1`
```