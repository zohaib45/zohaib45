
#                                                   👋 Hi, I'm Zohaib Hassan

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=00C2FF&center=true&vCenter=true&width=800&lines=Network+Engineer;Cloud+%26+Security+Enthusiast;Building+Scalable+University+Networks;Identity+%26+Access+Management+Specialist">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Networking-Expert-blue?style=for-the-badge&logo=cisco">
  <img src="https://img.shields.io/badge/Cloud-Azure%20%7C%20AWS-orange?style=for-the-badge&logo=icloud">
  <img src="https://img.shields.io/badge/Security-802.1X%20%7C%20RADIUS-red?style=for-the-badge&logo=shield">
  <img src="https://img.shields.io/badge/System-Engineer-green?style=for-the-badge&logo=linux">
</p>

---

## 🚀 About Me

* 🎓 Working in **University IT Infrastructure**
* 🌐 Designing **Enterprise Campus Networks (Core + Access)**
* 🔐 Implementing **802.1X, RADIUS, Identity-Based Access**
* ☁️ Exploring **Azure, AWS & Hybrid Identity**
* ⚙️ Focused on **Scalable & Secure Architectures**

---

## 🧠 Skills & Expertise

### 🌐 Networking

* Cisco (Core, Access, VLAN Design)
* MikroTik (Routing, Firewall, QoS, Load Balancing)
* UniFi Wireless Deployment
* Inter-VLAN Routing, STP

### 🔐 Security

* 802.1X (WPA2-Enterprise)
* FreeRADIUS + Google Secure LDAP
* Network Segmentation
* Firewall Design (pfSense, Fortinet alternatives)

### ☁️ Cloud & Identity

* Azure AD (Entra ID)
* Google Workspace (SSO, Secure LDAP)
* AWS (Free Tier, IAM)
* Hybrid Identity Architecture

### 💻 Systems

* Windows Server (AD, DNS, DHCP, WDS)
* Ubuntu Server / Linux Networking
* Git, Automation Basics

---

## 🧩 Architecture Diagrams

### 🏫 Campus Network Architecture

```mermaid
flowchart LR
    Internet --> Firewall
    Firewall --> Core[Nexus Core Switch]
    Core --> Access1[Cisco Access Switch - Floor 1]
    Core --> Access2[Cisco Access Switch - Floor 2]
    Core --> Access3[Cisco Access Switch - Floor 3]

    Access1 --> AP1[UniFi APs]
    Access2 --> AP2[UniFi APs]
    Access3 --> AP3[UniFi APs]

    Core --> ServerVLAN[Servers VLAN]
    ServerVLAN --> Radius[FreeRADIUS Server]
    ServerVLAN --> AD[Windows Server / Services]
```

---

### 🔐 Identity-Based Access Flow (802.1X + Google LDAP)

```mermaid
sequenceDiagram
    participant User
    participant AP as UniFi AP
    participant Radius as FreeRADIUS
    participant Google as Google Secure LDAP
    participant MikroTik

    User->>AP: Connect to WiFi
    AP->>Radius: Authentication Request (802.1X)
    Radius->>Google: Validate Credentials
    Google-->>Radius: Success / Fail
    Radius-->>AP: Accept + VLAN Assignment
    AP-->>MikroTik: Apply Policy
    MikroTik-->>User: Internet Access (Policy Based)
```

---

## 📂 Featured Projects

### 🏫 University Campus Network

* Multi-floor VLAN-based architecture
* Cisco Core + Access + UniFi WiFi
* High availability & segmentation

---

### 🔐 Identity-Based Internet System

* FreeRADIUS + Google Secure LDAP
* Dynamic VLAN assignment
* Role-based bandwidth control (Students / Faculty / Admin / VIP)

---

### ☁️ Hybrid Identity Design

* Azure AD + Google Workspace integration
* SSO architecture planning
* Scalable user authentication

---

### 📡 VoIP Deployment (FreePBX)

* Department-wise extensions
* SIP trunk integration
* Internal communication system

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=tokyonight">
</p>

---

## ⚡ Current Focus

* 🔐 Zero Trust Network Architecture
* ☁️ Azure Identity & Access Management
* 📊 Centralized Logging (SIEM concepts)
* 🧠 Advanced Network Security

---

## 📫 Connect With Me

* 💼 LinkedIn: (Add link)
* 📧 Email: (Add email)

---

<p align="center">
  ⭐ Building secure, scalable, and intelligent networks.
</p>
