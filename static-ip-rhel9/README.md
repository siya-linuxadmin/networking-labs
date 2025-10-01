# Project: Configure Static IP in RHEL 9 VM (VMware Workstation)

## 🎯 Objective
Set a **persistent static IPv4 address** for a Red Hat Enterprise Linux (RHEL 9) server running inside **VMware Workstation**, so the server can be accessed consistently via SSH and for hosting services.

---

## 🖥️ Environment
- **Host Machine:** Windows 11  
- **Hypervisor:** VMware Workstation Pro  
- **Guest OS:** Red Hat Enterprise Linux 9.5 (Plow)  
- **Network Mode:** NAT (VMware built-in DHCP, 192.168.147.0/24)  
- **Interface:** `ens160`

---

## ⚙️ Steps

### 1. Verify Network Interface
```bash
ip a
