This lab simulates a penetration test inside a controlled home environment.

Goal:
Attempt to brute-force SSH credentials on an Ubuntu machine (victim) from a Kali machine (attacker) using Hydra.

| Role     | Machine    | IP             | OS          |
| -------- | ---------- | -------------- | ----------- |
| Attacker | Kali Linux |  192.168.64.4  | Debian/Kali |
| Target   | Ubuntu     | `192.168.64.3` | Ubuntu      |


Result:
Bruteforce attempt was blocked due to lockout protections (connection refused + banned).
This demonstrates real-world defense mechanisms like intrusion detection and anti-bruteforce controls.

🛠 Lab Setup
Role	Machine	IP	OS
Attacker	Kali Linux	Your Kali IP	Debian/Kali
Target	Ubuntu	192.168.64.3	Ubuntu

SSH user created on target:

nate
