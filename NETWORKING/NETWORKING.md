## **NETWORKING**



Networking is a foundational skill for DevOps engineers because:



###### \### ✅ **Infrastructure Design**



DevOps engineers design scalable infrastructure involving routers, firewalls, servers, and connectivity. Understanding networking protocols helps in building reliable environments.



###### \### ✅ **Application Deployment**



Deploying applications requires configuring load balancers, servers, and network routes to ensure performance and availability.



###### \### ✅ **Automation**



Automation tools like Ansible and Puppet help configure network devices and services automatically.



###### \### ✅ **Monitoring \& Troubleshooting**



Monitoring traffic patterns, identifying bottlenecks, and diagnosing network failures require networking knowledge. 



---



###### \## 📡 **The OSI Model**



The OSI model explains how data travels across networks using seven layers:



| Layer        | Purpose                              |

| ------------ | ------------------------------------ |

| Physical     | Transmission of raw bits             |

| Data Link    | Framing, addressing, error detection |

| Network      | Routing and congestion control       |

| Transport    | End-to-end communication             |

| Session      | Dialog control and synchronization   |

| Presentation | Encoding, encryption, compression    |

| Application  | User-facing services                 |



This layered architecture simplifies network design and troubleshooting. 



---



###### \## 🌍 **TCP/IP Reference Model**



TCP/IP is the practical implementation used on the internet. It consists of four layers:



\* Application

\* Transport

\* Internet

\* Network Access



It enables communication across both public internet and private networks. 



---



###### \## 📦 **Internet Protocol (IP)**



IP operates at the network layer and provides \*\*best-effort delivery\*\* of packets called datagrams.



\### Key Datagram Fields



\* Version

\* Header Length

\* Total Length

\* Identification \& Fragmentation

\* TTL (Time To Live)

\* Protocol

\* Source \& Destination Address



Fragmentation allows packets to traverse networks with different frame sizes. 



---



###### \## 🧭 **IP Address Classes**



Traditional IPv4 addressing includes:



| Class | Prefix | Usage           |

| ----- | ------ | --------------- |

| A     | 0      | Large networks  |

| B     | 10     | Medium networks |

| C     | 110    | Small networks  |

| D     | 1110   | Multicast       |

| E     | 1111   | Reserved        |



Although classful addressing is largely replaced by CIDR, it remains important for conceptual understanding. 



---



\## 🔁 ARP, RARP and ICMP



\### 🔹 ARP (Address Resolution Protocol)



Maps IP addresses to MAC addresses within a LAN.



\### 🔹 RARP



Allows a device to discover its IP using its MAC address.



\### 🔹 ICMP



Used by routers and hosts to send error and diagnostic messages (e.g., ping). 



---



###### \## ⚡ **Transport Layer Protocols**



\### 🔹 UDP



\* Lightweight

\* Connectionless

\* Minimal overhead

\* Used in streaming, DNS



\### 🔹 TCP (implicit in document context)



\* Reliable

\* Connection-oriented

\* Flow \& congestion control



UDP packets contain source port, destination port, length, and checksum fields. 



---



###### \## 📁 **Application Layer Protocols**



\### 📂 FTP



Transfers files between client and server systems over TCP/IP.



\### 🌐 DNS



Converts domain names into IP addresses. DNS queries can be:



\* Recursive

\* Iterative

\* Non-recursive



DNS caching improves performance for repeated queries. 



---



###### \## 🧠 **DHCP (Dynamic Host Configuration Protocol)**



DHCP automatically assigns:



\* IP address

\* Subnet mask

\* Gateway

\* DNS



This removes manual configuration and enables centralized IP management using leases. 



---



###### \## 🔐 **SSH and Secure Communication**



SSH provides encrypted remote access and replaced insecure protocols like Telnet.



\### SSH Architecture



\* Transport Layer → encryption \& integrity

\* Authentication Layer → identity verification

\* Connection Layer → multiplexed sessions



SSH protects against spoofing and interception attacks. 



---



###### \## 📤 **SCP (Secure Copy Protocol)**



SCP securely transfers files between local and remote systems over SSH.



\### Example



```bash

scp file.txt user@server:/path/

```



Benefits:



\* Encryption

\* Authentication

\* Permission preservation 



---



###### \## 🌐 **cURL Utility**



cURL is a CLI tool for sending requests and transferring data via multiple protocols such as HTTP, FTP, and SMTP.



\### Common Uses



\* Download files

\* API testing

\* Debugging

\* Automation scripts 



---



###### \## 🕸️ **Network Topologies**



\### 🔹 Bus



Single backbone cable.



\### 🔹 Ring



Circular connection with token passing.



\### 🔹 Star



Central hub connecting nodes.



\### 🔹 Mesh



Fully interconnected network.



\### 🔹 Tree



Hierarchical structure.



\### 🔹 Hybrid



Combination of multiple topologies. 



---



###### \## 🧾 **CIDR Notation**



CIDR enables flexible IP allocation using prefix notation (e.g., `/24`).

It improves routing efficiency and simplifies subnetting. 



---



###### \## 🔑 **MAC Address**



A MAC address is a unique 48-bit hardware identifier assigned to network interfaces.



\### Types



\* Unicast → single device

\* Multicast → group

\* Broadcast → all devices 

