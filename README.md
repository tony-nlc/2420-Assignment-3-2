# ACIT 2420 Assignment 3 Part 2
This assignment will set up two servers with a load balancer. The servers will support HTML rendering and file downloading. 

## Tech Stack
* nginx
* DigitalOcean
* ufw
* bash
* git

## Task 1: Create Droplets
Let's start with creating two virutal machine (droplet) on DigitalOcean by click the `Create` button at the top right. Then, click `Droplets`.

![alt text](image.png)

Then, select the region, image (Arch for this project), CPU options, SSH keys and make sure you put `web` as the tah and change `Quantity` to 2 Droplets.

Then, click `Create Droplet`

## Task 2: Create Load Balancer
The we will need create load balancer on DigitalOcean by click the "Create" button at the top right. Then, click `Load Balancers`

![alt text](image.png)

Then, select the datacenter region and under `Connect Droplets` select `web` tag. Then scroll down and click Create.