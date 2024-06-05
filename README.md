# Active-Directory-Installation

<p align="center">
<img src="https://i.imgur.com/HPRl0Uw.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Active Directory Deployed in the Cloud (Microsoft Azure)</h1>
Hello! In this tutorial I will install Active Directory within Azure Virtual Machines. We'll asume in this tutorial that you have two Virtual Machines on Azure already created. One VM using Windows server 2022(Domain Controller) which I will be installing Active Directory on and another VM using Windows 10(the Client) that I will join later to the Domain controller.

<b>*Note: Client VM is a mock of a random computer at a school, buisness, etc that is connected to a Domain Controller*</b>

<br/>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Active Directory Domain Services

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2> Set the Domain Controller's Private ip to Static</h2>
<b> On the Azure Portal click Domain controller > Click Networking > Click  Network Interface</b>
