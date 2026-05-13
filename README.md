# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:


<img width="832" height="523" alt="image" src="https://github.com/user-attachments/assets/94edec81-69b8-4239-8fb8-5d9e35f7df12" />

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="637" height="435" alt="image" src="https://github.com/user-attachments/assets/6a025d3e-f508-48a6-b9d7-91aa0a563102" />

 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
<img width="532" height="241" alt="image" src="https://github.com/user-attachments/assets/b498387a-9109-40a5-bcbf-abe4015202e7" />





In Kali issue the following commands:
sudo dsnifff
## OUTPUT:


<img width="766" height="125" alt="image" src="https://github.com/user-attachments/assets/cdf2f4bc-6c17-4509-a17c-fe1f0563a7d5" />


Invoke the wireshark and examine the various menus  and controls of the tool:

<img width="1914" height="807" alt="image" src="https://github.com/user-attachments/assets/04700a63-99f3-45d0-a1f1-8b131a0790d7" />

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
