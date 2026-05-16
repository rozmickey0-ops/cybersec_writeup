# Defensive Security Lab Writeup

**Date:** 2026-17-05  
**Environment:** SOC Simulation Lab / Practice VM  
**Note:** All tasks were performed in an authorized lab environment. Do not test these techniques on systems you don’t own.

---

### Task 1: Main Goal of Defensive Security

**Question:**  
What is the main goal of defensive security?

**Options:**  
1. Detect and respond to attacks  
2. Attack systems to find flaws  

**Answer:**  
**Detect and respond to attacks**

**Explanation:**  
Defensive security focuses on protecting systems, detecting malicious activity, and responding to incidents to minimize damage. Offensive security is about finding flaws through testing.

---

### Task 2: Detect Suspicious Activity

**Scenario:**  
Joe, a SOC analyst, sees alerts on the monitoring dashboard. The goal is to identify the suspicious source IP.

**Steps Taken:**
1. Opened the monitoring dashboard in the lab VM.
2. Reviewed recent alerts and logs.
3. Looked for unusual source IPs with repeated or abnormal requests.

**Answer:**  
[Suspicious Source IP from your lab dashboard]

**What I Learned:**  
SOC analysts use dashboards to spot patterns that don’t match normal user behavior. Identifying the source IP is the first step in investigation.

---

### Task 3: Identify the Attack

**Scenario:**  
After finding the suspicious IP, the next step is to figure out what the attacker is trying to do by checking URL discovery attempts.

**Steps Taken:**
1. Investigated the attack logs in the dashboard.
2. Viewed the "URL Discovery Attempts" list.
3. Checked the latest entry to see what URL the attacker tried to access.

**Answer:**  
[Latest URL from "URL Discovery Attempts" in your lab]

**What I Learned:**  
Attackers often probe for hidden or admin URLs. Monitoring these attempts helps identify reconnaissance activity.

---

### Task 4: Stop the Attack

**Scenario:**  
Containment is required. The attacker’s IP needs to be blocked using a firewall rule.

**Steps Taken:**
1. Reviewed the security actions already completed in the lab.
2. Added the attacker IP `32.122.195.63` to the "Add Firewall Rule" textbox.
3. Selected "BLOCK" from the dropdown and clicked "Apply".

**Answer:**  
[Flag/Success message displayed after blocking the IP]

**What I Learned:**  
Containment is a core part of incident response. Blocking malicious IPs stops further damage while investigation continues.

---

### Key Takeaways
- Defensive security = detect, analyze, respond, contain.
- Always verify findings in a lab before applying them in real environments.
- Document each step so others can follow and verify your investigation.
