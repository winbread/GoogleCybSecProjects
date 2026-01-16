<h1>Install software in a Linux distribution</h1>

 

<h2>Description</h2>
Project consists of installing and uninstalling applications using a packet manager (APT). 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Bash Shell</b> 
- <b>APT</b>
- <b>Suricata</b>
- <b>tcpdump</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
First lets verify we have apt installed by entering apt
 When installed apt displays basic usage information. This includes the version information and a description of the tool: <br/>
<img src=""/>
<br />
<br />
Use the APT package manager to install Suricata by running `sudo apt install suricata`. <br />
 Note: running sudo is important, only users with elevated permissions (sudo users) can install or uninstall applications<br/>
<img src="https://github.com/winbread/GoogleCybSecProjects/blob/main/Install%20Software%20in%20a%20Linux%20Distribution/images/sudoaptinstall.png">
<br />
<br />
Lets verify we have successfully installed Suricata <br/>When Suricata is installed, version and usage information is listed:<br/>
<img src="https://github.com/winbread/GoogleCybSecProjects/blob/main/Install%20Software%20in%20a%20Linux%20Distribution/images/verifysuricatainstall.png"/>
<br />
<br />
Uninstall Suricata by running `sudo remove suricata`.: <br/>
 Note: running sudo is important, only users with elevated permissions (sudo users) can install or uninstall applications<br/>
<img src="https://github.com/winbread/GoogleCybSecProjects/blob/main/Install%20Software%20in%20a%20Linux%20Distribution/images/removesuricata.png" />   
 <br/>  
<br />
<br />
Verify successfull uninstallation of Suricata:  <br/>
<img src="https://github.com/winbread/GoogleCybSecProjects/blob/main/Install%20Software%20in%20a%20Linux%20Distribution/images/removesuricataverify.png"/>
<br />
<br />
Install tcpdump running sudo install tcpdump  <br/>
<img src="https://github.com/winbread/GoogleCybSecProjects/blob/main/Install%20Software%20in%20a%20Linux%20Distribution/images/installtcpdump.png"/>
<br />
<br />
Verify installation via apt list --installed  <br/> Look through the alphabetical list of installed applications until you find tcpdump. You will also notice Suricata does not appear on this list.  <br/>
<img src="https://github.com/winbread/GoogleCybSecProjects/blob/main/Install%20Software%20in%20a%20Linux%20Distribution/images/aptlistinstall.png"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
