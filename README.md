# Task 5 - Capture and Analyze Network Traffic Using Wireshark

## Objective
The goal of this task is to capture live network packets, filter them by protocol, and analyze at least three different protocols.

## Tools Used
- Wireshark (Free and Open-Source)
- Windows Command Prompt / Linux Terminal

## Steps Performed
1. Installed Wireshark and Npcap.
2. Selected the active network interface.
3. Started packet capture.
4. Generated traffic by browsing websites and pinging servers.
5. Stopped capture after 1 minute.
6. Applied protocol filters in Wireshark (`dns`, `http`, `tcp`, `icmp`).
7. Identified at least three protocols:
   - **DNS**: Domain resolution queries and responses.
   - **HTTP/HTTPS**: Web traffic.
   - **ICMP**: Ping traffic.
   - **TCP**: Transport layer stream.
8. Saved capture as `.pcap` file.
9. Wrote a short report.

## Findings
- DNS lookups are visible in plain text.
- HTTPS encrypts payloads but TCP handshakes are still readable.
- ICMP packets are simple and easy to analyze.

## Files in Repository
- `Detailed experience of performing the task.
- `README.md` - This file.

## Outcome
This task improved my protocol analysis skills and gave me hands-on experience with Wireshark to troubleshoot and study network activity.
