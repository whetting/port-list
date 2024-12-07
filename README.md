# PortNumbersReferenceList
For reference information collection Common port collection
# Download
git clone https://github.com/whetting/PortNumbersReferenceList.git
# Use
root@kali:~$ nmap -p port_default.txt 192.168.0.0 #You can replace port default.txt with a different file
Starting Nmap 7.80 ( https://nmap.org ) at 2024-12-07 10:00
Nmap scan report for 192.168.0.1
Host is up (0.0012s latency).
PORT     STATE SERVICE
21/tcp   open  ftp
22/tcp   open  ssh
80/tcp   open  http
443/tcp  open  https

Nmap done: 256 IP addresses (4 hosts up) scanned in 2.34 seconds

root@kali:~$ 

## This is for reference only and needs to be combined with the actual situation