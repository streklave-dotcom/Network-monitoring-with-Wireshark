# GitHub Documentation – Network Monitoring with Wireshark

## Project Overview

This project focuses on network monitoring and packet analysis using Wireshark. The goal is to help users understand network activity, inspect traffic, and identify unusual or suspicious behavior on a network.

The project demonstrates how Wireshark can:

* Capture network packets in real time
* Analyze network communication
* Filter and inspect traffic
* Improve cybersecurity awareness
* Detect unusual network activity

This project is useful for students, IT professionals, and beginners learning about cybersecurity and network analysis.

---

# Resources Used

## Official Resources

* [Wireshark Official Website](https://www.wireshark.org?utm_source=chatgpt.com)
* [Wireshark GitHub Repository](https://github.com/wireshark/wireshark?utm_source=chatgpt.com)
* [Wireshark Documentation](https://www.wireshark.org/docs/?utm_source=chatgpt.com)

## Additional Learning Resources

* Online tutorials about packet analysis
* Cybersecurity networking videos
* Practice labs for network monitoring

---<img width="850" height="450" alt="DfiSzGFRJu5RMaabgZLswrmwgRSAQRBCUNIVfLN2FSn3V4fBmFn45a2NhtjAWa6sngnlXdu9x1c8VFypVwoREz-ZnMaljynVVUzGKeIcfDkGypYrTW21m3edJgvGV15Bu7nIED7hdlMFHmBZTE6XSlxsanwfgEIpmvohgLGWr2Y" src="https://github.com/user-attachments/assets/c7bc50e7-4597-4dcd-95b5-216a1c2c2c6c" />


# Step-by-Step Installation and Configuration

## 1. Download Wireshark

1. Go to the official website:

   * [Download Wireshark](https://www.wireshark.org/download.html?utm_source=chatgpt.com)

2. Select your operating system:

   * Windows
   * macOS
   * Linux

3. Download the installer.

---

## 2. Install Wireshark

### Windows Installation

1. Run the installer.
2. Accept the license agreement.
3. Keep the default installation settings.
4. Install **Npcap** when prompted.

   * Npcap allows packet capturing on Windows.
5. Finish the installation.

### Linux Installation

Use the following commands:

```bash
sudo apt update
sudo apt install wireshark
```

Allow non-root users to capture packets if asked during installation.

---

## 3. Launch Wireshark

1. Open Wireshark.
2. Select a network interface:

   * Wi-Fi
   * Ethernet
3. Click the blue shark fin icon to start packet capture.

---

## 4. Capture Network Traffic

1. Start the capture.
2. Open websites or applications to generate traffic.
3. Observe packets appearing in real time.

Examples of traffic:

* DNS requests
* HTTP/HTTPS traffic
* ICMP ping packets

---

## 5. Use Filters

Wireshark filters help analyze specific traffic.

Examples:

```text
http
dns
tcp
ip.addr == 192.168.1.1
```

Filters make packet analysis easier and more organized.

---

## 6. Analyze Packets

1. Select a packet.
2. Expand packet details:

   * Ethernet
   * IP
   * TCP/UDP
3. Review packet contents and communication details.

---

# Troubleshooting Notes

## Problem: No Packets Appearing

### Cause

Wrong network interface selected.

### Solution

* Stop the capture.
* Select the correct Wi-Fi or Ethernet adapter.
* Restart packet capture.

---

## Problem: Permission Errors

### Cause

Administrator/root access required.

### Solution

* Run Wireshark as Administrator on Windows.
* Use sudo privileges on Linux if needed.

---

## Problem: Npcap Not Installed

### Cause

Packet capture driver missing on Windows.

### Solution

* Reinstall Wireshark.
* Make sure Npcap is selected during installation.

---

## Problem: Too Much Traffic Displayed

### Cause

Large amounts of packets captured.

### Solution

Use filters such as:

```text
http
dns
tcp.port == 80
```

---

# Challenges Encountered

## 1. Understanding Packet Analysis

At first, packet data was difficult to understand because of technical networking terms and protocols.

### How It Was Solved

* Watched tutorials
* Practiced reading packets
* Learned basic networking concepts

---

## 2. Managing Large Amounts of Traffic

Thousands of packets appeared during captures, making analysis confusing.

### How It Was Solved

* Used filters
* Focused on specific protocols
* Captured traffic for shorter periods

---

## 3. Permission and Installation Issues

Administrator access and Npcap installation caused setup problems.

### How It Was Solved

* Reinstalled required drivers
* Used administrator permissions
* Followed official documentation

---

## 4. Learning Advanced Features

Wireshark contains many advanced tools and options that take time to learn.

### How It Was Solved

* Started with basic packet capture
* Practiced simple filtering
* Used official documentation and tutorials

---

# Conclusion

This project demonstrates the importance of network monitoring in cybersecurity. Using Wireshark helped improve understanding of network communication, packet inspection, and traffic analysis.

The project also provided hands-on experience with:

* Monitoring network activity
* Detecting unusual traffic
* Using packet filters
* Understanding cybersecurity concepts

Wireshark is a powerful tool for learning and improving network security awareness.
