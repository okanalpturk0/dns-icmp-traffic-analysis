# DNS and ICMP Traffic Analysis

## Project Overview
This project investigates a simulated website connectivity incident using tcpdump network traffic logs. The analysis focuses on DNS resolution failures and ICMP port-unreachable messages.

## Objectives
- Analyze DNS queries sent over UDP port 53.
- Interpret ICMP error messages.
- Identify the likely cause of a DNS resolution failure.
- Recommend troubleshooting and remediation steps.

## Tools and Protocols
- **Tool:** tcpdump
- **Application protocol:** DNS
- **Transport protocol:** UDP
- **Internet-layer protocol:** ICMP
- **Related web protocol:** HTTPS

## Key Findings
The packet log showed repeated DNS queries to destination port 53, followed by ICMP messages reporting that the UDP port was unreachable. This indicates a DNS resolution issue that prevented normal access to the website.

## Recommended Remediation
Verify DNS service availability, review firewall and access control rules, test DNS resolution, and confirm website access after remediation.

## Scope
This is a training case study based on a provided scenario and packet-log description. The underlying root cause has not been independently verified.

## Deliverables
- `incident-report.md` — Incident summary, findings, and recommendations.

## Skills Demonstrated
Network traffic analysis, DNS troubleshooting, protocol identification, incident documentation, and root-cause hypothesis development.
