# openvpn-install-script

OpenVPN install script for **Debian, Ubuntu, Fedora, CentOS, Arch Linux, Oracle Linux, Rocky Linux and AlmaLinux.**

This script will install OpenVPN to your own secure VPN server in just a few seconds.<br/>
**(2 different person can use OpenVPN **simultaneously** for free)**

## Usage

First, get a cheap VPS from Hostinger

 1. First, visit this link to get %20 discount (in order to get the discount you need to visit this link before making a purchase):
    <a href="https://www.hostinger.com/referral?REFERRALCODE=YPVCANEROEJW" target="_blank">https://www.hostinger.com/referral?REFERRALCODE=YPVCANEROEJW</a>
    
2. In the visited link page, Click on **Services** (the top menu) -> **VPS Hosting** then click on **"Choose Plan"** button and select **KVM 1** plan and complete the purchase.
3. Go to your **Browser Terminal** in your VPS admin page.
4. Type in the command under to get the automatic OpenVPN install script:
   
```bash
curl -O https://raw.githubusercontent.com/angristan/openvpn-install/master/openvpn-install.sh
chmod +x openvpn-install.sh
```

5. Then run this command:

```sh
./openvpn-install.sh
```
6. Follow the instructions to install the server. (You can select the default choices, no worries) It will ask you a **"Client Name:"** at some point. The client name you provide will determine the name of the **.ovpn** file. For example if you type in **MyVPN** the resulting file will be **MyVPN.ovpn**. You will use that file to connect to your VPN in your PC/Mac/iPhone/Android.

7. After the automatic installation is completed, use a SFTP client (like https://winscp.net/) to log in to your VPS with your IP address, username and password and then download your **.ovpn** file to your computer.
8. Download **OpenVPN Connect** (https://openvpn.net/client/) to your PC/Mac/iPhone/Android (on the cient you want to connect to your VPN)
9. Load your **.ovpn** file in **OpenVPN Connect** application.
10. That's it! You're connected to the internet using your own VPN inside your VPS

Video guide: https://youtu.be/CboBqogUdwI?t=87 (Instructions are in Turkish but you can open auto generated subtitles for English or just follow the video muted)
