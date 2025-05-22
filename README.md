# 🤖 Security Automation: Shuffle SOAR Integration Lab

This project explores how to automate repetitive SOC analyst tasks by integrating Shuffle SOAR with Wazuh, TheHive, VirusTotal, and custom logic to create an automated alert triage and response pipeline.

---

## 🎯 Objective

To implement a lightweight SOAR platform (Shuffle) and integrate it with a SIEM and case management system to reduce response time, enrich alerts, and eliminate manual effort in the security triage process.

---

## 🧠 Skills Learned

- SOAR Playbook Design  
- API Integration with VirusTotal, Wazuh & TheHive  
- Workflow Automation using Shuffle.io  
- Alert Triage and Enrichment Logic  
- Security Event Parsing & Analysis  
- JSON Data Handling and Trigger Conditions  
- Automation Debugging & Optimization

---

## 🛠️ Tools Used

- [Shuffle.io](https://shuffler.io/)  
- [Wazuh](https://wazuh.com)  
- [TheHive Project](https://thehive-project.org/)  
- [VirusTotal API](https://www.virustotal.com/gui/home/upload)  
- [Docker](https://www.docker.com/)  
- [DigitalOcean](https://www.digitalocean.com/)  
- Custom Python & Webhook Scripts

---

## 🔬 Walkthrough

### 1. ⚙️ Setup & Config

- Deployed TheHive on DigitalOcean using Docker  
- Connected Shuffle to Wazuh to receive real-time alerts via webhook  
- Connected VirusTotal API for IOC enrichment  


---

### 2. 🔁 Playbook Design

- Triggered on incoming Wazuh alerts  
- Parsed JSON for IPs, hashes, and domains  
- Queried VirusTotal for reputation analysis  
- Automatically created or updated a case in TheHive  
- Tagged alerts with threat level indicators  


---

### 3. 🧪 Testing & Optimization

- Simulated multiple alert types (brute force, malware, etc.)  
- Verified enrichment accuracy  
- Implemented error-handling for failed API calls  
- Reduced triage time by ~70% through automation  


---

## 🔐 Key Findings

- Shuffle is a powerful open-source SOAR for custom use-cases  
- API-driven enrichment improves context for every alert  
- Workflow-based automation drastically reduces manual effort  
- Alerts can be auto-triaged, enriched, and sent to analysts with full IOC breakdowns  


---

## 📸 Screenshots

![Screenshot 2025-05-22 123412](https://github.com/user-attachments/assets/eb011f10-9457-4241-8745-7ca312c6d067)
![Screenshot 2025-05-21 134608](https://github.com/user-attachments/assets/2f49a92e-7061-467c-9c20-6f573b2c575e)
![Screenshot 2025-05-21 144926](https://github.com/user-attachments/assets/9bf5845d-134e-4664-9093-12031a318e9c)
![Screenshot 2025-05-21 134608](https://github.com/user-attachments/assets/f8698fc6-bff8-4a89-bebe-41fd3ec7dd25)
![Screenshot 2025-05-22 121850](https://github.com/user-attachments/assets/8adae0ea-9bbf-4475-9982-09dcee0a37a9)
![Screenshot 2025-05-21 082226](https://github.com/user-attachments/assets/5ad5fd16-9f36-49b2-9b7a-5f86c434c76c)
![Screenshot 2025-05-21 115749](https://github.com/user-attachments/assets/4ff9952d-b02a-4f01-bd8c-8d38a94d363d)
![Screenshot 2025-05-21 122132](https://github.com/user-attachments/assets/1509d005-88a1-4789-b3ba-1a150bfa7fd4)
![Screenshot 2025-05-22 123512](https://github.com/user-attachments/assets/18a0b091-e381-4c08-affe-b1dad0b5e902)
![Screenshot 2025-05-22 122014](https://github.com/user-attachments/assets/67358b53-b4b8-41f7-abf1-70f3eb6bd5e7)
---

## 🗣️ Conclusion

Building this automation layer showed how powerful SOAR tools can be in a modern SOC. Instead of wasting time on repetitive tasks, this setup allows analysts to focus on real threats.

---

## 💬 Feedback

Got tips, feedback, or want to collaborate on SOAR use-cases?  
Reach out on [LinkedIn](https://www.linkedin.com/) or open an issue.

