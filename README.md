<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Make a subscription
- Create Resource Group and Virtual Machine
- Download Web Platform Installer with SQL 5.5 and PHP applications
- Install OSticket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/evGxnXz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Microsoft Azure scroll down for free subcription using your email address and password. For first time use of this service you will be able to recieve a $200 azure credit towards your account which will expire within 30 days.
</p>
<br />

<p>
<img src="https://i.imgur.com/GYoua2d.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now you must create a Resource Group and a Virtual Machine using windows 10. You will than copy and paste the public IP address from you VM into the remote desktop connection application. You will log in utilizing the name and password you created when setting up your VM. Within the VM download webplatforminstaller app, when download is complete open application.

</p>
<br />

<p>
<img src="https://i.imgur.com/JHJjL2a.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Within the VM download webplatforminstaller app, type in MySQL 5.5 at the top right corner and install. Install simple versions of x86 PHP up until 7.3, fix any failures if required. Install PHP Manager 1.5.0 for IIS 10 and Microsoft Visual C++. 
</p>
<img src="https://i.imgur.com/KY4kOnf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Download Osticket and than Extract and copy the “upload” folder INTO c:\inetpub\wwwroot from your file explorer. Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”. Type in the search menu IIS restart server so that it can update with osticket folder. Go to sites -> Default -> osTicket, on the right, click “Browse *:80. Enable extensions in the IIS
</p>
<img src=</p>
<img src="https://i.imgur.com/KY4kOnf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<p>
