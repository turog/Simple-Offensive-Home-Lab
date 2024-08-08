# Simple-Offensive-Home-Lab
Raspberry Pi Offensive Home Lab in a attacking scenario using Docker Containers.

Objective

The Simlpe Offensive Home Lab project aimed to establish an attacking scenario using docker containers. The scenario is as follows: An attacker running a simple C2 framework (Kali machine) routes its fradulent request through a reverse proxy (Nginx machine) to mask its identity from the target (Ubuntu machine). 

Skills Learned

Gained an understanding of containerization concepts and practical application.
Gained an understanding of self signing certificates as it relates to deploying HTTPS instead of HTTP


Tools Used

Docker
Kali
Ubuntu 
OpenSSL

Steps (For a detailed guide follow Grant Collins' in-depth course: https://www.youtube.com/watch?v=MshVeYlpE90&t)

1. Install Docker Engine and Establish Basic Setup of Container Environment 
2. Deploy Base Image Containers (Kali,NGINX,Ubuntu)
3. Download packages 
4. Establish Basic Connection with docker
5. Connect Reverse Proxy 
6. Establish Connection Back to C2 

