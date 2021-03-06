# DC38032 Dynamic Analysis Workshop

## Preparation

 - Copy files from flash to your hard-drive
	 - MacOS High Sierra - folder with virtual machine.
	 - DC38032.zip - Archive with malware.
	 - VMware - Copy installation file based on your OS.
	 - Burp suite community edition - Copy installation file based on your OS.

 - Install VMware Fusion or Workstation.
 - If you are using Linux/Windows as host system, you need to patch your VM.
	- git clone https://github.com/DrDonk/unlocker.git
	-  **Windows**
	- On Windows you will need to either run cmd.exe as Administrator or using
	Explorer right click on the command file and select "Run as administrator".
	- win-install.cmd
	- **Linux**
	- chmod +x lnx-install.sh
	- ./lnx-install.sh
	
 - After that you can run virtual machine in VMware
 
## Burp Installation

 - Install Burp Suite Community Edition
 - Set network configuration on your Virtual Machine to NAT
 - Add your host IP address to burp suite proxy listeners list
 - Open Burp Suite Listener address on your VM and download CA cert.
 - Double click on downloaded certificate and select system keychain
 - Open keychain access, select system storage, open certificates tab. 

## Monitor installation
https://www.fireeye.com/services/freeware/monitor.html
 - Open monitor.dmg
 - Move Monitor app to Applications folder
 - Run Monitor app.
