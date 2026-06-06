# Advanced IPv4 Subnetting & Structural VLSM Optimization

This directory contains my engineering designs for corporate IP address allocation, dividing networks efficiently into functional zones.


## 📐 Project 1: Class C Subnetting Layout
* **What I Did & The Problem:** I designed a standard Class C subnetting topology. The main problem was dividing a single block into equal subnets without creating
high address waste for smaller zones.
* **The Solution & Real-World Use:** I configured fixed-length subnet masks to create clean network boundaries. In the real world, this is used in small businesses
to separate basic departments like Admin and Sales.


## 📐 Project 2: Class B Subnetting Layout
* **What I Did & The Problem:** I expanded the design to a Class B subnetting topology. The challenge was managing a much larger pool of IP addresses and setting up
correct default gateways for higher host capacities.
* **The Solution & Real-World Use:** I calculated and applied custom masks tailored for larger networks. This is used in large enterprise campuses or universities 
that need thousands of IP addresses distributed across multiple buildings.


## 📐 Project 3: 3-Department VLSM Design
* **What I Did & The Problem:** I engineered a VLSM design for 3 distinct departments. The problem was that each department required a completely different number
of hosts, making standard fixed subnetting highly wasteful.

* **The Solution & Real-World Use:** I used Variable Length Subnet Masking to give each department a mask matching its exact size. In real-world corporate networks,
this saves IP spaces and optimizes the company’s address scope.


## 📐 Project 4: 5-Department VLSM Design
* **What I Did & The Problem:** I built a more complex VLSM topology to support 5 corporate departments. The main challenge was avoiding overlapping subnets while
calculating prefixes from the largest department down to the smallest.
* **The Solution & Real-World Use:** I structured a precise addressing matrix that achieved absolute zero address waste across all 5 zones. This is standard 
practice in ISPs and modern corporate branches to maximize scalability and secure routing paths.




