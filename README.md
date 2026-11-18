ZeroTrust Internet Block Monitor V1.5.2-DEV
Description
A read-only Windows network diagnostic and monitoring tool designed to investigate blocked and permitted Internet connections, with particular attention to Windows Filtering Platform (WFP), firewall activity, and DNS traffic.
What it does
Monitors and analyzes Windows network connection activity.
Identifies blocked and permitted connections.
Correlates network events with applications, processes, IP addresses, ports, and protocols.
Examines Windows Filtering Platform (WFP) filter information to help identify which firewall rules are responsible for blocking traffic.
Detects and reports DNS-related activity, including DNSCrypt Proxy configuration and connections.
Generates diagnostic reports for troubleshooting and investigation.
Includes automated self-tests to verify diagnostic functionality.
Safety: Operates in read-only mode. It does not create, modify, or delete Windows Firewall rules or change network configuration.
Limitation: Encrypted upstream DNS traffic cannot always be conclusively identified as DoH or DNSCrypt using connection information alone.
