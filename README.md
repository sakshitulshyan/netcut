# Netcut
Disable the net of anyone present in your network

Directly download arp_spoofer.py and netcut.py

ONLY WORKS IN LINUX

Run the following commands in terminal:

1.) apt-get install build-essential python-dev libnetfilter-queue-dev

2.)pip install NetfilterQueue

3.)sudo apt install net-tools -y

4.)sudo pip3 install scapy

5.)iptables -I FORWARD  -j NFQUEUE --queue-num 0

6.)python arp_spoofer.py -t [target IP] -s [sppofing IP]

7.)open a new terminal or split the terminal

8.)python netcut.py


