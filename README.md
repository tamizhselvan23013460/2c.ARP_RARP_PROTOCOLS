# 2c.i.SIMULATING ARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP:
### Client program:
![client arp pro](https://github.com/tamizhselvan23013460/2c.ARP_RARP_PROTOCOLS/assets/150231370/942db244-448e-4911-a4f8-abdef55e26b1)

### Server program:
![image](https://github.com/tamizhselvan23013460/2c.ARP_RARP_PROTOCOLS/assets/150231370/8bf8fc4c-1abd-4de8-98f9-3c969fc644ea)

## OUPUT - ARP:
### Client output:
![client arp](https://github.com/tamizhselvan23013460/2c.ARP_RARP_PROTOCOLS/assets/150231370/1769ac26-ea1a-4dc4-bada-dd99c26ee686)

### Server output:
![server arp](https://github.com/tamizhselvan23013460/2c.ARP_RARP_PROTOCOLS/assets/150231370/c91da2ab-eba9-4729-b7aa-5fcabb1d7f33)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.

# ii.SIMULATING RARP PROTOCOLS
## AIM:
To write a python program for simulating RARP protocols using UDP.

## ALGORITHM:
### Client:
1.Start the program
2.Using datagram sockets UDP function is established.
3.Get the MAC address to be converted into IP address.
4.Send this MAC address to server.
5.Server returns the IP address to client.

### Server:
1.Start the program.
2.Server maintains the table in which IP and corresponding MAC addresses are stored.
3.Read the MAC address which is send by the client.
4.Map the IP address with its MAC address and return the IP address to client.

## PROGRAM - RARP:
### Client program:
![CLIENT ARAP PRO](https://github.com/tamizhselvan23013460/2c.ARP_RARP_PROTOCOLS/assets/150231370/adf5cc17-0265-4410-85db-12fc02ff93e3)

### Server program:
![image](https://github.com/tamizhselvan23013460/2c.ARP_RARP_PROTOCOLS/assets/150231370/714ea7ca-25d9-4d84-9867-d943346b061b)


## OUPUT -RARP:
### Client output:
![CLIENT ARAP](https://github.com/tamizhselvan23013460/2c.ARP_RARP_PROTOCOLS/assets/150231370/7eba82af-049a-4710-939f-5d58b43b1473)

### Ser

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
