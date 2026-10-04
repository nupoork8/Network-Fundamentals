# Day 1: Network Fundamentals & Client-Server Architecture

## 1. Network Basics
**What is a Network?**
At its core, a network is simply two or more devices connected to share resources, data, or services. Just like roads connect cities, a network connects computers, servers, and smartphones so they can communicate.

**Local Area Network (LAN) vs. Wide Area Network (WAN)**
*   **LAN:** A private network confined to a small, physical space like a single home, office building, or university campus. 
*   **WAN:** A massive network that connects multiple LANs across cities, countries, or the globe. The public internet is the largest WAN.

## 2. Client-Server Architecture
Most modern enterprise networks use a Client-Server model to function and deliver data.

*   **The Server:** A powerful, centralized computer that holds data or hosts services (like an internal company website, an email server, or a database). It waits for requests and serves the data.
*   **The Client:** An end-user device (like a laptop, workstation, or smartphone) that requests information from the server.
*   **The Communication:** Clients and servers need precise rules to talk. They use **IP Addresses** (like a digital home address) to find each other and protocols like **HTTP** to request and deliver web pages.

## 3. Cisco Packet Tracer Topology: Practical Lab
To put theory into practice, I built a functional LAN and simulated a client-server web request using Cisco Packet Tracer.

### Network Components Used
*   **End Devices:** 2 PCs (Clients) and 1 Web Server.
*   **The Switch (Layer 2):** The central connection hub that physically links the PCs and the Server together to form the private LAN.
*   **Cabling:** Copper straight-through cables.

### Project Execution Steps
1. **Built the LAN:** Placed the PCs and Server into the workspace and physically cabled them to the central Switch.
2. **Configured IPs:** Assigned static IPv4 addresses to the Client (`192.168.1.10`) and the Server (`192.168.1.100`) so they could locate each other.
3. **Enabled Services:** Spun up an active HTTP web service on the centralized Server.
4. **Verified Connectivity:** Simulated an end-user request by navigating to the Server's IP address in the Client's web browser, successfully pulling the web page data across the network.

 <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a786c99d-ec0d-4b47-885a-7afb94e9e9df" />
