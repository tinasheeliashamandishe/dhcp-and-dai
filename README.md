<h1>DHCP Snooping</h1>

<h2>Description</h2>
This lab will configure DHCP snooping.<br/>
<br/>
DHCP snooping is a security feature implemented on network switches to prevent malicious or unauthorized DHCP (Dynamic Host Configuration Protocol) servers from being introduced into a network. DHCP is used to automatically assign IP addresses to devices on a network, but if an unauthorized DHCP server is introduced, it could assign incorrect IP addresses or provide other malicious configuration parameters, leading to network connectivity issues or security breaches.<br/><br/>

The purpose of DHCP snooping is to monitor DHCP messages that are exchanged between DHCP clients and servers.
<br />

<h2>Environments Used </h2>

- <b>Packet Tracer</b>

<h2>Lab walk-through:</h2>

<p align="center">
<h4>Lab Topology:</h4>
In this Lab DHCP Snooping will be configured on the switch. <br/>
Router2 has been configured as the DHCP server.
The lab consists of 2 router, 1 switch, and 2 computers. <br/>
<img src="https://i.imgur.com/KYHv5GW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h4>DHCP Snooping Configuration:</h4> 
Before DHCP is configured the devices do not have IP address settings yet.<br/>
<img src="https://i.imgur.com/oZCZNgZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<br />
