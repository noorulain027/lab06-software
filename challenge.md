# Lab 06 Challenge

## 1. Install htop
Command: sudo apt install -y htop
Observation: htop displays CPU usage.

## 2. Apache2 version
Command: apt show apache2 | head -4
Version: 2.4.58-1ubuntu8.17

## 3. Installed packages
Command: apt list --installed | wc -l
Count: 15

## 4. Alpine container
Command: sudo docker run --rm alpine echo "Hello from Alpine"
Output: Hello from Alpine

## 5. Docker files
Key: /etc/apt/keyrings/docker.asc
Sources: /etc/apt/sources.list.d/docker.sources

## 6. Remove htop
Command: sudo apt remove -y htop
Verification: htop command not found after removal.
