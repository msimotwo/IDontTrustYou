# Zero Trust Architecture (ZTA) Implementation 🚀

Welcome! This project showcases how to build a **Zero Trust Architecture (ZTA)**—a modern approach to securing sensitive systems. Whether you're new to cybersecurity or an experienced professional, you'll find practical insights here.

---

## 🌟 What is Zero Trust Architecture (ZTA)?
Zero Trust means: **Never trust, always verify**. It’s about ensuring that:
- Everyone is **verified** before accessing resources.
- Access is limited to what’s **necessary** (least privilege).
- Activities are **monitored continuously** for threats.

---

## 🛠️ How Did I Implement ZTA?
Here’s a step-by-step breakdown of how I applied ZTA principles:

1. **🔑 Identity Verification**  
   - Used **Okta** and **Duo Security** for **multi-factor authentication (MFA)**.  
   - Goal: Verify every user’s identity before granting access.

2. **🔒 Network Micro-Segmentation**  
   - Deployed **VMware NSX** to divide the network into secure segments.
   - **VMware NSX** is a network virtualization and security platform that enables micro-segmentation, automated networking, and zero-trust security within cloud and on-prem environments. It’s important because it isolates workloads, controls east-west traffic, and prevents lateral movement, reducing the attack surface and enhancing overall security.
   - Why? To isolate critical assets and prevent attackers from moving laterally.

3. **📜 Access Controls**  
   - Implemented **Role-Based Access Control (RBAC)** and **Policy-Based Access Control (PBAC)**.  
   - Purpose: Ensure users only access what they need—nothing more.
   - 📜 Access Controls (What is RBAC/PBAC?)  
   - **RBAC (Role-Based Access Control)** → Grants access based on job roles (e.g., HR can access HR files, IT Admins can manage all systems).  
   - **PBAC (Policy-Based Access Control)** → Uses conditions like **location, device, or time** (e.g., files are only accessible from corporate devices or during work hours).  
   - **Why?** Ensures **least privilege access** and strengthens Zero Trust security.
  
 

4. **📈 Continuous Monitoring**  
   - Integrated **Splunk** and **Microsoft Sentinel** for real-time activity monitoring.  
   - Result: Detected unusual behavior quickly and responded to threats.

---

## 🧰 Tools and Technologies Used
Here’s the tech stack that powered this project:  
- **MFA:** Okta, Duo Security  
- **Network Segmentation:** VMware NSX  
- **SIEM Tools:** Splunk, Microsoft Sentinel  

---

## 🎯 What Was Achieved?
- **Improved Security:** Reduced unauthorized access risks by implementing strong identity verification and micro-segmentation.  
- **Hands-On Learning:** Gained expertise in modern tools like **VMware NSX**, **Splunk**, and **Okta**.  
- **Scalable Solution:** Created a foundation that aligns with the **Zero Trust Framework**, ready for future enhancements.  

---

## 🔍 Who Is This For?
This project is perfect for:  
- **Beginners** looking to understand Zero Trust principles.  
- **Cybersecurity enthusiasts** exploring tools like MFA, SIEM, and network segmentation.  
- **IT professionals** curious about designing secure architectures.  

---

## 🌱 What’s Next?
I plan to:  
- Explore **Cloud Access Security Broker (CASB)** integration.  
- Automate responses to threats with **SOAR platforms**.  
- Share configuration examples and code snippets (stay tuned!).

---

💡 **Want to Learn More?**  
Feel free to connect with me or ask questions! I’d love to share insights!
