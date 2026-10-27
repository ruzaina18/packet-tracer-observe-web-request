# Packet Tracer – Observe Web Request

## Overview
This project demonstrates client-server communication using Cisco Packet Tracer. It explores DNS name resolution, HTTP web requests, and TCP traffic between a client PC and a web server.

## Objectives
- Verify connectivity to a web server using ping.
- Observe DNS hostname resolution.
- Access a webpage using HTTP.
- Examine the HTML source code hosted on a web server.
- Analyze TCP and HTTP packet flow in Simulation Mode.

## Tools Used
- Cisco Packet Tracer
- Command Prompt
- Web Browser
- Simulation Mode

## Lab Procedure

### 1. Verify Connectivity
Used the following command on the External Client:

`ping ciscolearn.web.com`

Observed the resolved IP address and checked connectivity to the web server.

### 2. Access the Web Server
Opened `ciscolearn.web.com` in the client's web browser and examined the webpage returned by the server.

### 3. Examine HTML
Accessed the server's HTTP service and inspected the `index.html` file to understand how HTML creates the webpage displayed in the browser.

### 4. Analyze HTTP and TCP Traffic
Created a Complex PDU with the following settings:
- Application: HTTP
- Source device: External Client
- Destination: ciscolearn.web.com
- Starting source port: 1000
- Periodic interval: 120 seconds

Observed packet events in Simulation Mode with TCP and HTTP filters enabled.

## Key Concepts Learned
- DNS translates domain names into IP addresses.
- HTTP enables communication between web clients and servers.
- HTML defines the structure and content of webpages.
- TCP establishes connections and supports reliable data delivery.
- Packet Tracer Simulation Mode helps visualize packet flow and protocol interactions.

## Results
The lab demonstrates the process of requesting a webpage from a web server and observing the associated TCP and HTTP traffic.

## Evidence
Screenshots of DNS resolution, the webpage, and packet simulation are stored in the `screenshots/` folder.

## Skills Demonstrated
Networking fundamentals, DNS, HTTP, TCP/IP, client-server communication, packet analysis, and Cisco Packet Tracer.
