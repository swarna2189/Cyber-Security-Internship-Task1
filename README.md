# Cyber-Security-Internship-Task1
Network Scanning and Reconnaissance using Nmap

### Objective

To perform network reconnaissance by identifying open ports, running services, and operating system information using Nmap.

### Tools Used

* Kali Linux
* Nmap 7.98

### Target

Localhost (127.0.0.1)

### Command Used

```bash
sudo nmap -sV -A 127.0.0.1
```

### Results

* Host was active.
* Port **8000/tcp** was found open.
* HTTP service detected:

  * SimpleHTTPServer 0.6
  * Python 3.13.12
* Operating system identified as Linux (Kernel 5.x/6.x).

### Learning Outcomes

* Learned how to perform network reconnaissance.
* Identified active ports and running services.
* Understood basic service and OS detection using Nmap.

### Repository Structure

```
report/
screenshots/
README.md
```
