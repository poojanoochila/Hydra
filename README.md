# Hydra
Here I am sharing my knowledge on Hydra

## Overview
Hydra is a fast and powerful password brute-forcing tool used by cybersecurity professionals and penetration testers to test login security on various services and protocols.

## What I Learned
- Basics of brute-force attacks
- How weak passwords can be exploited
- Using wordlists for password attacks
- Importance of strong authentication mechanisms
- Defensive techniques against brute-force attacks
- Done practical on Molly's webpage  

## Protocols Supported by Hydra
- SSH
- FTP
- HTTP/HTTPS
- SMB
- Telnet
- RDP
- Many more

## Basic Hydra Command

```bash
hydra -l admin -P rockyou.txt ssh://TARGET-IP
