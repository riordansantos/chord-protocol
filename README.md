# Chord-protocol

This project has two components, the Peer (```Node_DHT.py```) and the Client(```Client.py```).

## How to run the project:

### The Peer:
For the first node joining the ring ```python3 Node_DHT.py port_number``` here "port_number" is the port at which the node will listen for requests. It will start at the port 9000.

   For any forth coming nodes into the ring ```python3 Node_DHT.py <port number of new node> <port number of existing node here>``` "port number of new node" is the port at which the node will listen for requests and "port number of existing node" is the port number of any of the other pre existing nodes in the ring.
  


## The Client:
To run the client, use: ```python3 Client.py```<br/>
The client is menu driven where we need to provide inputs like the port number of the node which the client wants to connect to and then the option according to the task the client wants to perform like insert, search, delete etc.



