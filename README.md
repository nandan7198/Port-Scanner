# Port Scanner
Port Scanner is a Java-based network utility tool with a graphical user interface (GUI) that allows users to scan for open ports on a target host. It provides features for resolving hostnames to IP addresses and specifying a range of ports to scan.

## Features

<li>Identifying Open Ports: Port scanners are used to determine which network ports are open and listening for incoming connections. Open ports can represent potential security vulnerabilities.

<li>Security Assessment: By scanning for open ports, security professionals can assess the security posture of a network or system and identify potential weaknesses that need to be addressed.

<li>Firewall Configuration: Port scanners can help administrators verify that their firewall rules are properly configured to allow or block specific types of traffic.

<li>Network Mapping: Port scans can be used to create network maps that show which services are running on which devices, helping with network management and troubleshooting.

<li>Intrusion Detection: Port scanning can be an indicator of malicious activity or unauthorized attempts to access a network. Intrusion detection systems often use port scanning as a signature of an attack.


### Host Resolve

The "Host Resolve" option enables users to input a website address or hostname and resolve it to an IP address. This feature simplifies the process for users who want to scan a host but might not know its IP address.

### Port Range

The "Port Range" option allows users to define a custom range of ports to scan on the target host. Users can specify a start port and an end port to narrow down the scope of the scan, making it more efficient and customizable.

### Scan Button

The "Scan" button triggers the port scanning process. When clicked, the application checks for open ports on the specified target. Users can monitor the progress of the scan in real-time.

### Results Display

The results of the port scan are displayed in the textarea below the IP address textbox and button. The open ports discovered during the scan are listed here, making it easy for users to review the results.