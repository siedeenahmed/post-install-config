<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objective</h2>

- Configure Roles, Departments, Teams, Agents, Users, and SLAs

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/30MaEal.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/UfvbB2C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, we configure the Roles, Departments, and Teams. Here we configured the role "Sumpreme Admin" with all permissions, the department "System Administrators", and the team "Level II Support".
</p>
<br />

<p>
<img src="https://i.imgur.com/jVyLT1d.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Ihu30lQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Second, we configure Agents and Users and asisgn them to the Roles, Departments, and Teams that we created. Here we created the agents Jane and John and the users Karen and Ken.
</p>
<br />

<p>
<img src="https://i.imgur.com/bqwfcQh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lastly, we configure SLAs. Here we create three levels with varying severity: Sev-A for tickets to be addressed within one hour, Sev-B for tickets to be addressed within four hours, Sev-C for tickets to be addressed within 8 hours.
</p>
<br />
