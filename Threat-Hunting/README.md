**Hunting an APT with Splunk**

**Introduction:**

Welcome to the report on hunting an Advanced Persistent Threat (APT) using Splunk Enterprise and Enterprise Security. This report documents the process of threat hunting based on the Boss of the SOC 2017 dataset, which was developed by Splunk's Security Specialist team. The objective of this workshop is to provide hands-on experience in identifying and mitigating APTs using Splunk's powerful analytics capabilities.

**Lab Environment and Dataset:**

The dataset utilized in this workshop was generated in August 2017 by members of Splunk's Security Specialist team. The lab environment comprised Windows endpoints equipped with the Splunk Universal Forwarder and Splunk Stream. These forwarders were configured with best practices for Windows endpoint monitoring, including a comprehensive deployment of Microsoft Sysmon and optimal settings for Windows Event logging. Additionally, the environment featured a Palo Alto Networks next-generation firewall for traffic capture and web proxy services, along with Suricata for network-based Intrusion Detection System (IDS).

**Scene:**

In this workshop, participants assume the persona of Alice Bluebird, a security analyst at Frothly, a company specializing in knock-off versions of classic beers. Grace Hoppy, Frothly's CEO, has been notified by the FBI of an intrusion by the Taedonggang APT, an East Asian threat actor targeting innovative western brewing supply companies like Frothly. Alice's task is to investigate the intrusion and understand the adversary's actions.

We will be hunting for indicators/signs for the following stages in the MITRE ATT&CK Framework.

  1. Reconnaissance
  2. Initial Access
  3. Account Persistence
  4. Lateral Movement
  5. Scheduled Tasks
  6. Powershell Empire
  7. Data Staging
  8. Exfilteration    a. using DNS    b. via FTP
  9. Clearing Logs

**Aim:**

The primary goal of this project series is to expose participants to various adversary techniques and illustrate how threat hunters can develop hypotheses to hunt for specific adversary capabilities using Splunk. This project is one of eleven hunts in the workshop series, each focusing on different aspects of APT detection and mitigation.
