<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create Virtual Machines
- Creat and instal Active Directory
- Create Domain
- Join Client-1 to your domain(myrishiahdomain.com)

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/agpkN8q.png"/>
</p>
<p>
This picture shows where i created my two virtual machines one that was the main domain and the other one that i used to join later on. To creat the virtual machine have to go azure microsoft and make sure they both were in the same location and in the same resource group. 
</p>
<br />

<p>
<img src="https://i.imgur.com/hzzpQmS.png"/>
</p>
<p>I
Here where I installed and configued the active directory this was done by going into server manager and then going to roles and featured wizard.
</p>
<br />

<p>
<img src="https://i.imgur.com/rIaQLnC.png"/>
</p>
<p>
In this stage is where create my domain (myrishiahdomain.com) and then join client-1 access wto be able to login in as a domain user. 
</p>
<br />
