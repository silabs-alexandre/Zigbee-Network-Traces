# Basic Network Policies captures Project
![Type badge](https://img.shields.io/badge/Type-Virtual%20application-green)
![Technology badge](https://img.shields.io/badge/Technology-Zigbee-green)
![License badge](https://img.shields.io/badge/License-Zlib-green)
![SDK badge](https://img.shields.io/badge/SDK-v4.1.0-green)
 
## 1. Summary
To connect to a network, you can use either the well-known key which is "ZigbeeAlliance09" or install-code, there is also the touchlink commissionning. When a device is joining with the well-known key, the TC is then sending the NWK key encrypted with the well-known link key. 

## 2. List of Projects
**Joining Policies** : 
* Joining_InstallCode : To join a network with install-code
* Joining_WellKnownKey : Join with the well-known key "ZigbeeAlliance09"

**TC Policies** :
* TC_GlobalLinkKey : Use a global TC link key for all nodes 
* TC_HashedLinkKey : Use a global TC Link key which is hashed by the eui64 of each node
* TC_UniqueLinkKey : Use a random unique TC link key for each node joining the network

**NWK Key Update** :
* Network_KeyUpdate : Demonstrate the network update with broadcast

**App Link Keys**
* appLinkKey : Use a unique APP Link key to secure communication between 2 nodes on a network

**Messaging** :
* Multicast_SwitchLight : Project to send multicast message to a specific Group

## 3. Structure of Projects
You can see in all the projects the following structures : 
* Src : Source code files used for the project
* SimplicityStudio : Export files for all the projects
* Traces directly into the directory
* README : Explains how to use the project
