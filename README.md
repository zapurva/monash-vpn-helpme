## monash-vpn-helpme

# How to access Monash VPN via Linux (Ubuntu)

1. Go to ```https://vpn.monash.edu```
2. Select the 1-Monash_Authcate group from the drop down menu. Enter your Monash username and password 
3. Download the file ```vpnsetup.sh```
4. Grant the file permisson to execute: 
```
chmod +x /path/to/vpnsetup.sh
``` 
and then execute from source: 
```
sudo ./vpnsetup.sh
```
This will install Cisco AnyConnect

5. Navigate to: 
```
cd ~
cd /opt/cisco/anyconnect/bin/
```
and to open GUI: 
```
sudo ./vpnui
```
6. In this window, connect to ```vpn.monash.edu``` and give necessary permissions (trust certificates). Again, provide login details and you're connected!

# References

[1] https://answers.uillinois.edu/illinois/page.php?id=47640
[2] https://www.monash.edu/esolutions/network/vpn
