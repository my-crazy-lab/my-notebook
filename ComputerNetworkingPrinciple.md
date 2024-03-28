## Introduction 
- LAN 
- MAN 
- WAN 
- Full mesh 
- Bus 
- Star
- Ring 
- Tree
- broadcast 
- unicast: one sender to on receiver 
- multicast: send to N receivers 
- anycast 

## Services and protocols 
- a user interacts with a service through a SERVICE ACCESS POINT 
- interaction between user and service by using primitives
- connectionless service: UDP 
  - reliable connectionless service: TCP
  - unreliable connectionless service: UDP

## OSI
- physical layer
  - unit of information exchanges is bit, rate is bit/s
  - electrical cable
  - optical fiber
  - wireless
- data link layer
  - unit of information exchanges is frame
  - a frame is a finit sequence of bit
- network layer
  - exchanges packets
  - a packet is a finit sequence of bytes, transport by datalink layer inside frames
- transport layer
  - exchanges segments
  - a packet is a finit sequence of bytes, transport by network layer inside packets
- application layer
  - exchanges application data unit

## Application layer
- Big-Endians & Little-Endians
- ASCII
- BNF
  - use to define programming language (can define messages exchanges between L7)
  - 




