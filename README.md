# cisco_projects

<h2>Description</h2>
In this project,  a series of network scenarios with Cisco Packet Tracer is presented, which cover a wide range of networking concepts. These scenarios encompass everything from fundamental network connections to the design of resilient and secure networks. The project was done as a part of my accelerated cyber security training at the Fields Institute - University of Toronto.

<h2>1. Extended Access List Configuration for IPv4</h2>

The network illustrated in the provided figure was connected and configured, involving routers, computers, and servers with specific settings. For routers, fundamental configurations such as hostnames, passwords, and IP addresses for interfaces were established. Similarly, IP addresses, subnet masks, gateways, and DNS servers were set up for computers and servers, ensuring seamless connectivity.

Additionally, traffic routing was optimized through the implementation of default routes on Router 1 and Router 2, both guiding traffic through the S0/0 exit interface. Security was enhanced by strategically placing an extended ACL on Router 2 to block Telnet traffic from the LAN to the Web Server.

During testing, successful webpage display on the Web Server from Computer B was verified. ACLs were applied to Router 2's interface to limit Web Server access, and a similar approach was followed for an extended ACL that prevented ICMP traffic from Router 1's LAN to the File Server. Thorough testing confirmed secure and intended network operations.

<br />
<br />
<img src="https://github.com/sdkallullathil/cisco_projects/blob/3e6bd46f34b1fd1c870a149fbe6657e8a6cc3490/snl-1.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>2. IPSec Site-to-Site VPN</h2>

During the lab, a Site-to-site IPSec VPN was successfully configured in a provided scenario using Cisco Packet Tracer as the implementation environment. Devices were connected based on the network diagram, and essential configurations were applied to the routers. Basic setups for the hosts, including IP addresses, subnet masks, default gateways, and DNS server addresses, were also implemented.

Furthermore, EIGRP Dynamic Routing was configured on the routers, specifying advertised networks in autonomous system number 10. The network's functionality was tested by pinging from Computer A to Computer B while monitoring packet contents. A site-to-site VPN was established between Routers 1 and 3, involving key policy creation, shared key setup, defining allowed traffic, transforming sets, creating a crypto map, binding it to the interface, and troubleshooting.

Lastly, the setup was retested to confirm encrypted packet transmission from Computer A to Computer B. This lab experience significantly improved skills in configuring and troubleshooting intricate network setups, further enhancing proficiency in network implementation and security.
<br />
<br />
<img src="https://github.com/sdkallullathil/cisco_projects/blob/b6f746f1163210928f30ad3ac6267a0489cc7c22/snl3.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>3. EIGRP Configuration on a Cisco Router</h2>

Network connectivity was established according to the provided figure, and network settings were configured accordingly. Basic router configurations involving hostname assignment, password setup, and interface IP addressing were implemented. The settings for computers were adjusted to enable seamless communication. EIGRP Dynamic Routing was then configured on the routers to advertise specific networks within the autonomous system.

Validation of the configuration involved conducting PING tests between computers and inspecting routing tables. Additionally, the effects of changing the autonomous system number within EIGRP were explored. A comprehensive assessment of connectivity and routing tables ensured the network's optimal performance.
<br />
<br />
<img src="https://github.com/sdkallullathil/cisco_projects/blob/4378bfc13156d37b079e65db6b927fef8b0fec6a/lab5.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>4. Static NAT Configuration</h2>


The depicted network was established and configured. Router 1's adjustments, made through the console link to Computer A, encompassed hostname assignment ('Router1'), password settings, VTY password configuration, and IP assignment for FE0/0 and FE0/1 interfaces. Similar adjustments were applied to Computer A, involving IP settings.

Likewise, Router 2's configuration changes, executed via the console link to Computer B, included hostname assignment ('Router2'), password settings, VTY password definition, and IP configuration for FE0/0 and FE0/1 interfaces. Concurrently, adjustments were made to Computer D's IP settings.

Additionally, Static NAT was set up on Router 1 using specific internal and external addresses. To ensure data transmission between Computer A and Computer D, Static Routing was configured on both Router 1 and Router 2. Network performance was assessed through WireShark installation on Computer D and executing a PING command from Computer A to Computer D, observing the source IP address within the PING message.

<br />
<br />
<img src="https://github.com/sdkallullathil/cisco_projects/blob/ac1f4aa78414ea6de22bd70bea712917a8bc62db/lab4.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>5. Static Routing</h2>

The network depicted in the figure above was connected, and configurations were implemented as follows: On Router 1, essential tasks were performed, including hostname assignment, console, secret, and VTY password setup, as well as interface configurations for FE0/0 and S0/0. Router 2 underwent a similar basic configuration, involving hostname assignment, suitable passwords, and interface setup.
Regarding the computers, adjustments were made to their settings. For Computer A and Computer B, I defined necessary parameters like subnet masks, default gateways, and DNS server addresses. Likewise, Computer C and Computer D had their configurations updated accordingly.

Additionally, static routing was established on Router 1 to direct traffic for specific destinations, while Router 2 was configured similarly to route designated traffic.
To confirm the effectiveness of the setup, PING tests were conducted from Computer A to Computers C and D, ensuring seamless communication within the network.

<br />
<br />
<img src="https://github.com/sdkallullathil/cisco_projects/blob/ac1f4aa78414ea6de22bd70bea712917a8bc62db/lab4.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>6. Wireless Access Point Configuration</h2>

The task involves configuring an access point to create a wireless network and connecting client PCs to this network. Devices in the topology diagram are connected for this purpose. Initially, Router0 is configured as a DHCP server with a designated DHCP range. The access point is then configured by selecting Port 1 for the wireless link and making adjustments to the SSID (Fields), channel (1), and security type (WPA2-PSK) with a passphrase. Subsequently, the client laptop is configured to connect to the wireless network by selecting the Fields network and entering the passphrase. A connectivity test using the "ping" command is conducted to verify the network's operational status.

<br />
<br />
<img src="https://github.com/sdkallullathil/cisco_projects/blob/e505a70c608763bb4bd6e333558f98e46d17f480/lab6-1.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>7. Wireless Router Configuration</h2>

The lab aimed to establish a wireless network using a router and connecting clients to it. The setup began with adjustments made in the router's GUI configuration, involving changes in IP address and subnet mask. DHCP server settings were configured, specifying DHCP enabling, starting IP, and maximum DHCP hosts. Basic wireless settings were configured, setting the network mode, SSID, and channel. Security settings were established, defining security mode, encryption, and passphrase. The final step included client configuration for wireless connection and a connectivity test was performed through "ping" commands between client computers for network communication validation.

<br />
<br />
<img src="https://github.com/sdkallullathil/cisco_projects/blob/dd1a3149f18c33de9022c14ce399e2166ce7646c/lab6-2.png" height="90%" width="90%" alt="Disk Sanitization Steps"/>
<br />
<br />
