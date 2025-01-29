---
title: "HTB Certified Penetration Testing Specialist (CPTS) Exam Review"
date: 2025-01-29
categories: [Cybersecurity, Certifications, HackTheBox]
tags: [HTB, CPTS, Penetration Testing, Ethical Hacking]
layout: post
---

## Introduction

I recently earned the **Certified Penetration Testing Specialist (CPTS)** certification from **Hack The Box** (HTB). This post is a review of my experience preparing for the exam, what I learned, and my overall thoughts on the certification.

## What is CPTS?

The **HTB CPTS** certification focuses on real-world penetration testing techniques, covering various aspects such as:

- Network exploitation
- Active Directory attacks
- Post-exploitation techniques
- Privilege escalation
- Pivoting & Lateral Movement
- Attacking Windows & Linux
- Reporting

It is a hands-on, practical certification designed for security professionals looking to enhance their offensive security skills.

## My Experience

In 2024, I set a personal goal to earn a cybersecurity certification in 2025. I wanted something beginner-friendly, and while I explored several options, CPTS (Certified Penetration Testing Specialist) was not initially on my list. However, after consulting with my seniors and reflecting on my experience with Hack The Box Season 6 machines, I decided to take on the CPTS challenge.

In November 2024, I made the commitment and purchased the CPTS exam voucher. At the time, I felt confident in my skills and believed I could clear the certification without much difficulty. However, as I delved deeper, I realized that I needed to refine my knowledge and gain more hands-on experience before attempting the exam.

To better prepare myself, I decided to complete the DANTE Pro Lab from Hack The Box. This decision turned out to be a game-changer, as it provided me with practical, real-world penetration testing scenarios that strengthened my methodology and technical approach. My initial plan was to schedule the CPTS exam in December so I could start the new year as a certified penetration tester.

Just as I was about to schedule my exam, university finals approached. I knew that attempting the certification amidst my academic responsibilities would divide my focus and impact my performance in both areas. Instead of rushing, I made the difficult but wise decision to postpone the exam until mid-January, after my finals had concluded.

Once my exams ended, I took a well-deserved day of rest before fully immersing myself in my CPTS attempt. While preparing, I also considered doing the Zephyr Pro Lab, but after discussing with experienced peers, I learned that Zephyr wasn’t essential for CPTS—DANTE and the dedicated HTB CPTS module were sufficient. Trusting their advice, I focused entirely on the HTB module and refined my skills.


## Exam Experience

Before attempting the CPTS exam, I had to complete the HTB Academy Penetration Tester Path, which consists of 28 modules. This can be accessed through a student subscription for $8 per month or by purchasing cubes. It took me around two months to finish at my own pace. The CPTS exam itself started on January 14, 2024, and I had until January 23, 2024, to submit a detailed report. The exam consists of 14 flags, and at least 12 are required to pass. Each voucher includes two attempts, valid for a year.

The first two days were great since the university was off, and I made solid progress. However, I got stuck on one point for a couple of days, which made me feel exhausted and frustrated. Balancing the exam with university was tough, but I kept pushing forward. Eventually, I managed to capture all 14 flags, which was a huge relief. The next challenge was the report, and I had very little time left. I rushed through it but still managed to write a 150-page detailed report.

The final night before submission, I didn’t sleep at all, working non-stop to refine my report. Luckily, the day before the deadline was a university off-day, so I spent the entire day polishing it. Despite the exhaustion, achieving a perfect score and completing the report felt incredibly rewarding. The experience taught me perseverance, problem-solving, and time management. For anyone attempting the CPTS exam, I’d recommend pacing yourself, not panicking when stuck, starting the report early, and taking care of your health. It’s not just about passing—it’s about learning and growing.

## Tips and Recommendations:

### 1. Thorough Preparation
Prepare thoroughly and at a steady pace for each module in the Penetration Tester Path. The exam is challenging, with a significant focus on Active Directory exploitation, so give special attention to these areas. Practice using platforms like Dante, Zephyr, and Offshore labs to gain hands-on experience. While these labs will enhance your skills, remember the CPTS exam format differs from Pro Labs, so adapt accordingly.

### 2. Pivoting Techniques
Pivoting is an essential skill for penetration testing. While you can use any tool you're comfortable with, I recommend **ligolo-ng** as it's the best ( I tried 2-3 tools in exam). This tool proved to be much more effective for my needs.

### 3. Report Writing
Start documenting your findings early. This will prevent a last-minute rush when preparing your final report. Throughout the test, I documented screenshots, commands used, and a brief description of each step. I dedicated the last two days to finalizing my report using **SysReptor**. A template is provided with the exam, but reviewing professional penetration testing report examples beforehand will help you understand how to structure and present your findings effectively. 

### 4. Time Management
Proper time management is key to success. Allocate dedicated, uninterrupted time for the exam to ensure you're focused. Take regular breaks to avoid burnout and keep your mind sharp.

### 5. Practice CVSS Scoring & Attack Path Analysis
CVSS (Common Vulnerability Scoring System) is an important aspect of your report. Take time to understand how it works by practicing on different attack paths and vulnerabilities. Reviewing CVSS scoring guides will help you feel confident in accurately assessing the severity of vulnerabilities.

### 6. Build a Strategy and Stay Calm
Penetration tests can be mentally taxing, so having a clear strategy for tackling tasks helps you stay on track. Focus on high-priority areas first, and don't panic if you encounter obstacles. Stay calm, and use your network of resources to troubleshoot effectively.

### 7. Review Exam Materials and External Resources
Before taking the exam, go through any available study materials and external resources. Many students find success by studying past penetration testing reports, watching walkthrough videos, or reading blogs that cover common pitfalls and tips for passing the CPTS exam.


## Final Thoughts

Earning the **HTB CPTS** was a great learning experience, and I highly recommend it to anyone looking to improve their penetration testing skills. The hands-on approach makes it a valuable certification for cybersecurity professionals. 

## Tools

### General Exploitation & Post-Exploitation
- [HackTricks](https://book.hacktricks.xyz/) - Comprehensive pentesting and red teaming knowledge base.
- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) - Collection of useful payloads and bypass techniques.
- [Impacket](https://github.com/fortra/impacket) - Python collection for network protocols exploitation.
- [ligolo-ng](https://github.com/nicocha30/ligolo-ng) - Best Tool For tunneling.
- [evil-winrm](https://github.com/Hackplayers/evil-winrm) - WinRM exploitation tool for remote Windows access.
- [PowerView](https://github.com/PowerShellMafia/PowerSploit/tree/master/Recon) / [SharpView](https://github.com/tevora-threat/SharpView) - PowerShell/.NET tools for AD enumeration.
- [Mimikatz](https://github.com/gentilkiwi/mimikatz) - Credential dumping and Windows security exploitation.
- [LaZagne](https://github.com/AlessandroZ/LaZagne) - Credential retrieval from local systems.
- [Inveigh](https://github.com/Kevin-Robertson/Inveigh) - SMB/LLMNR/NBNS poisoning for credential capture.
- [Rubeus](https://github.com/GhostPack/Rubeus) - Kerberos exploitation for red teams.
- [SharpHound.ps1](https://github.com/BloodHoundAD/BloodHound/tree/master/Collectors) / [BloodHound](https://github.com/BloodHoundAD/BloodHound) - Active Directory attack mapping.

### Additional Tools for CPTS
- [Metasploit Framework](https://www.metasploit.com/) - The go-to exploitation framework.
- [Kerbrute](https://github.com/ropnop/kerbrute) - Enumerate and brute-force Kerberos usernames and passwords.
- [ADRecon](https://github.com/adrecon/ADRecon) - AD recon tool for auditing.
- [Certipy](https://github.com/ly4k/Certipy) - Exploiting Active Directory Certificate Services (ADCS).
- [Responder](https://github.com/lgandx/Responder) - SMB, NTLM, and LLMNR responder for credential capture.
- [Nishang](https://github.com/samratashok/nishang) - PowerShell scripts for penetration testing.
- [PsExec](https://docs.microsoft.com/en-us/sysinternals/downloads/psexec) - Remote execution on Windows systems.
- [Chisel](https://github.com/jpillora/chisel) - TCP/UDP tunneling tool (Alternative to Ligolo-Ng).
- [PetitPotam](https://github.com/topotam/PetitPotam) - NTLM relay attacks via MS-EFSRPC abuse.
- [SharpRDP](https://github.com/0xthirteen/SharpRDP) - Remote Desktop Protocol (RDP) attack toolkit.
- [NetExec](https://github.com/Pennyw0rth/NetExec) - Lateral movement tool.


## Resources

- [Hack The Box CPTS Official Page](https://www.hackthebox.com/)
- [My GitHub Projects](https://github.com/saadbukhari00)
- [Connect with Me on LinkedIn](https://www.linkedin.com/in/saadbukhari00)

---

If you're preparing for CPTS or have any questions, feel free to reach out! Good luck to all future CPTS candidates! 🚀 #HackTheBox #CPTS #PenetrationTesting #CyberSecurity
