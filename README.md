# InformationGathering


# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering
```
 DEVELOPED BY: Naveenaa A K
 REGISTER NO.: 212222230094
```

## PEN TESTING TOOLS CATEGORIES:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
![image](https://github.com/Shivaram2525/InformationGathering/assets/144226303/7ec4b2c6-6f70-4795-aade-429a9c7d3673)
### FINDING IP ADDRESS:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```

![image](https://github.com/Shivaram2525/InformationGathering/assets/144226303/3b5543df-ba93-47ae-a91b-b4d4c32afdd7)
### FINDING HOSTING COMPANY :
get further detail by using ip2location.com website.
![image](https://github.com/Shivaram2525/InformationGathering/assets/144226303/8f0118d8-a0ab-4fb5-aa3b-81abe84e64df)
### HISTORY OF THE COMPANY (WEBSITE) :
![image](https://github.com/Shivaram2525/InformationGathering/assets/144226303/329d4918-6874-46af-8c5b-9188372b74c0)
###  WEB SERVER FINGERPRINT :
### NETCAT:
```
nc 172.17.52.118 80
```
![image](https://github.com/Shivaram2525/InformationGathering/assets/144226303/863da250-1787-4d44-8416-dec9d460441b)
###  NMAP :
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
![image](https://github.com/Shivaram2525/InformationGathering/assets/144226303/1dccf14f-fa31-42ec-9daf-20f6f51dadbb)
### WHATWEB :
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
![image](https://github.com/Shivaram2525/InformationGathering/assets/144226303/5d368595-0e83-433b-a0d0-27fd766fa34b)
### httprint:InformationGathering:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
![image](https://github.com/Shivaram2525/InformationGathering/assets/144226303/e699c13a-becf-4a89-85d7-137afcb9fee9)
### TRACING THE LOCATION:
### TCP TRACEROUTE
```
sudo traceroute -T www.saveetha.ac.in
```
![image](https://github.com/Shivaram2525/InformationGathering/assets/144226303/f747bc0b-f76c-4230-b327-8132875c7e85)
## UDP TRACEROUTE
```
sudo traceroute -U www.saveetha.ac.in
```
![image](https://github.com/Shivaram2525/InformationGathering/assets/144226303/cb1d23eb-0255-41d4-8ad7-841ecd824533)
### ICMP TRACEROUTE
```
sudo traceroute  www.saveetha.ac.in
```
![image](https://github.com/Shivaram2525/InformationGathering/assets/144226303/ba0ed3a6-f7b0-42e6-8d95-944392cdc3ce)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
