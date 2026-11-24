Tusk Infostealer – CyberDefenders Lab

Lab Overview

- Platform: CyberDefenders
- Lab Name: Tusk Infostealer
- Category: Threat Intelligence
- Difficulty: Easy
- Estimated Time: 30 Minutes
- Status: Completed (9/9)

Objective

Analyze threat intelligence and malware configuration to identify TTPs, extract Indicators of Compromise (IOCs), and track cryptocurrency flow associated with the Tusk Infostealer campaign.

Tools & Resources Used

- Kaspersky Threat Intelligence Portal
- Threat Intelligence Reports

---

Investigation & Findings

Q1 – Malicious File Size

Question: In KB, what is the size of the malicious file?

Finding: "921.36 KB"

Evidence:

<img width="1831" height="218" alt="Screenshot (33)" src="https://github.com/user-attachments/assets/4ce55584-7238-4719-b218-67d26cf8c455" />


---

Q2 – Victim Identification

Question: What word do the threat actors use in log messages to describe their victims?

Finding: "mammoth"

Evidence:

<img width="688" height="138" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/e525182b-0a03-4a96-a99e-35a28cf6f221" />


---

Q3 – Malicious Website

Question: What is the name of the malicious website created to simulate the DAO platform?

Finding: "tidyme.io"

Evidence:

<img width="708" height="236" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/14eecda2-2fef-4722-8035-ffca0b106f0f" />


---

Q4 – Cloud Storage Provider

Question: Which cloud storage service was used to host malware samples?

Finding: "Dropbox"

Evidence:

<img width="747" height="592" alt="Screenshot (36)" src="https://github.com/user-attachments/assets/bee09383-989f-40a4-b82d-39c912b02cff" />


---

Q5 – Archive Password

Question: What is the password used for decompressing the archived data?

Finding: "newfile2024"

Evidence:

<img width="705" height="279" alt="Screenshot (37)" src="https://github.com/user-attachments/assets/fbd622b4-8c06-48f3-adf2-343c3d157a82" />


---

Q6 – Payload Download Function

Question: What function is responsible for retrieving the field archive from the configuration file?

Finding: "downloadAndExtractArchive"

Evidence:

<img width="726" height="306" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/60e7ec5f-47c3-47a1-99cc-ba146e3a7341" />


---

Q7 – Fake AI Translator

Question: What are the names of the legitimate translator and the malicious translator created by the attackers?

Finding:

- Legitimate Translator: "yous.ai"
- Malicious Translator: "voico.io"

Evidence:

<img width="715" height="500" alt="Screenshot (40)" src="https://github.com/user-attachments/assets/c8a3ff83-a65c-46d4-beab-fc8fef4e01b8" /> 


<img width="771" height="729" alt="Screenshot (41)" src="https://github.com/user-attachments/assets/9de8886f-46b3-4a5d-99df-b679028950dc" />



---

Q8 – StealC C2 Infrastructure

Question: What are the IP addresses of the StealC C2 servers used in the campaign?

Finding:

- "46.8.238.240"
- "23.94.225.177"

Evidence:

<img width="760" height="536" alt="Screenshot (42)" src="https://github.com/user-attachments/assets/da6aec52-2eeb-4340-914e-5de76f9b4eaf" />


---

Q9 – Cryptocurrency Wallet

Question: What is the address of the Ethereum cryptocurrency wallet used in this campaign?

Finding:
"0xaf0362e215Ff4e004F30e785e822F7E20b99723A"

Evidence:

<img width="1419" height="812" alt="Screenshot (43)" src="https://github.com/user-attachments/assets/ef91d13e-d7be-4e0a-b506-02ead7929143" />

---

Indicators of Compromise (IOCs)

Indicator| Value
Malicious File Size| 921.36 KB
Victim Identifier| mammoth
Malicious Website| tidyme.io
Cloud Storage| Dropbox
Archive Password| newfile2024
Download Function| downloadAndExtractArchive
Malicious Translator| volco.io
StealC C2 IP 1| 46.8.238.240
StealC C2 IP 2| 23.94.225.177
Ethereum Wallet| 0xaf0362e215Ff4e004F30e785e822F7E20b99723A

Conclusion

Successfully completed the Tusk Infostealer investigation by analyzing threat intelligence reports and malware configuration details.

The investigation identified the malicious infrastructure, victim identification terminology, cloud storage provider, payload retrieval function, associated StealC C2 servers, and the Ethereum wallet used in the campaign.

This lab improved practical skills in Threat Intelligence, IOC extraction, malware configuration analysis, infrastructure tracking, and cryptocurrency investigation.

Lab Status: 9/9 Questions Completed.
