# Chat Room using Python

This article gives an idea of – How to use Python to build a Chat Room server and allow multiple clients to connect in it. Before getting in deep, let’s first understand what sockets are. 

What are SOCKETS ?

If you google this term, you’ll get to know that “A socket is one endpoint of a two-way communication link between two programs running on the network.” When we talk with respect to Python - Socket programming is a method of connecting two nodes on a network in order to communicate with each other. In Python code we will use socket library, as it enables users to transfer information over the network

In this code, we will set up a socket on each end of the network and will allow a client to interact with other clients via the server i.e there will be two different scripts - Server Side Script and Client Side Script. We can run these scripts in the operating system command-line or terminal. When the server side script is running it waits for the client side connection. Once the connection is established, client and server can communicate with each other.
