
# 🛡️ Cybersecurity Lab Setup — Week 1, Task 1

As part of my **Network Walks Cybersecurity Lab**, I completed **Week 1 – Task 1: Setting up an isolated cybersecurity testing environment**.

The goal was to build a controlled virtual environment where I can safely practice cybersecurity techniques without affecting real-world systems.

## 🖥️ Lab Environment

### Virtualization

* **VirtualBox:** Latest recommended version
* **Attacking Machine:** Kali Linux 2026.3
* **Target Machine:** Windows 10
* **Network Mode:** NAT Network
* **Lab Subnet:** `10.0.0.0/24`
* **Kali Linux IP:** `10.0.0.2/24`

## ⚙️ Configuration Completed

I configured the following:

✅ Kali Linux installed successfully
✅ Windows 10 VM configured as the target machine
✅ Both VMs connected to the same **NAT Network**
✅ Kali Linux configured with `10.0.0.2/24`
✅ Kali Linux has full Internet access
✅ Clipboard sharing enabled
✅ File drag-and-drop enabled
✅ Shared folder configured from the host machine
✅ `/MyKaliPics` shared folder configured
✅ Successfully tested Internet connectivity through Mozilla Firefox

After completing the configuration, I opened Kali Linux and tested the network connection using the browser. Everything was working as expected.

## 🎯 Purpose of the Lab

This environment will serve as my **isolated and controlled cybersecurity laboratory** for authorized security testing and hands-on learning.

Some of the activities I will be practicing include:

* 🔎 Network reconnaissance
* 🌐 Port scanning
* 🛡️ Vulnerability assessment
* 📡 Packet analysis
* 🔐 Web application security testing
* 💥 Exploitation practice
* 🧪 Security-tool experimentation

The Kali Linux VM will act as my **attacking/security-testing machine**, while the Windows 10 VM will provide a controlled target environment.

## 📚 What I Learned

This task helped me understand that before performing penetration testing, I need to first build a properly isolated environment.

Rather than experimenting against systems I don't own, I can use virtual machines to create a safe environment where I can learn, break things, troubleshoot them, and rebuild them.

**Lab first. Learn safely. Test responsibly.**

### 🚀 Next Step

With the basic infrastructure working, I'm ready to move on to the next Network Walks task and begin introducing practical reconnaissance and security-testing activities into the lab.

#Cybersecurity #NetworkSecurity #PenetrationTesting #KaliLinux #VirtualBox #EthicalHacking #CybersecurityLab #VAPT #NetworkWalks #HandsOnLearning
