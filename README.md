# Rakhat


## Overview

Rakhat - a set of deliberately exploitable VM’s designed to provide practice for penetration testing. This set includes 2 machines, named Blake-Sploitable and Corey, that each include a variety of exploits and attack vectors. 

Blake-Sploitable is much more susceptible to exploitation than Corey, and is designed to provide practice for low-level attacks and exploits. Corey is only accessible from Blake-Sploitable or a remote login, and has much more stringent security measures. This machine is designed for low to moderate level exploits. 

We suggest these machines are used in tandem on a local, host-only network for the best experience. It’s important to note that these machines are designed for practice only, and are not designed for business or personal use, and should not be allowed to access an external network. 


## Installation

Download the Rakhat file, and extract to your VM folder.

*Please note these machines were designed on VMWare and may not function properly on VirtualBox*

Linux Users: 
1. You can figure this out

Mac OS Users:
1. Start VMWare on your host machine
2. File -> Import or the + symbol -> Import 
3. Click 'Choose File' and navigate to to the folder containing the extracted VM and choose the VMDK file and press open. 
4. Continue to the next page and update the name if you perfer. 
5. Once it has loaded, press 'Customize Settings'
6. Click 'Network Adaptor' and change this to 'Private to my Mac'

Windows Users:
1. Start VMWare on your host machine.
2. Click "Open Virtual Machine' and navigate to the folder containg the extracted VM, choose the VMX file and press open.
2. Right-click on the VM name in the list and choose 'Settings', and change the 'Network Adaptor' to 'Host-Only'.

Repeat these instructions with both machines. 



