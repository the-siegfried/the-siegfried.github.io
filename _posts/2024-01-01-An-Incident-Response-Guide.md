---
layout: post
title: An incident response guide
tags: [business, cyber, security]
---
 
How you and your business can create an efficient plan for responding to a cyber security attack. 

Cybersecurity attacks and breaches are almost inevitable. It is how you respond to them that makes all the difference. So, what is the best way to prevent an attack from becoming a full-scale breach? Preparation! 

It’s only after experiencing a breach that many organisations realise that if they had only an effective incident response plan in place before the attack, they could have avoided a lot of costs, pain, and unnecessary disruption.

This guide is intended to help your business develop its own framework for cybersecurity incident response planning to thwart an adversary before there’s no turning back. The recommendations you will find in this guide are based on my own real-world experiences and those of the amazing incident response teams I have had the pleasure of working with in the past. And these are not your average Joe’s either. These teams have had to respond to some of the most significant cyber attacks you’ve seen in the papers, including the ones you’ve never heard of.

 
## Cybersecurity incident response plan ⚠️
There are ten key steps to an effective incident response plan:

1. Stakeholder discovery
2. Critical asset identification
3. Testing your reflexes
4. Preventative tooling
5. Visibility maximisation
6. IAM implementation
7. Investigation tooling
8. IR action definition
9. Awareness training
10. Resource for combat

Let’s take a closer look at each of them.

 
## 1. Stakeholder discovery 👪
The planning and definition of an effective incident response plan do not solely sit on the shoulders of your organisation's security team. In the event of an incident, almost every department in your organisation will have a part to play to ensure the response is correctly coordinated. Thus, you must first determine who should be involved and what duties they must carry out in the event of an attack. This list of stakeholders typically includes senior management, legal, public relations, IT, and, of course, your security department. 

This stakeholder identification exercise should be completed before any planning exercises take place. Far too often, individuals jump the gun and start or complete planning before identifying and involving the key stakeholders, which leads to crucial information missing from your incident response plan. Most importantly, don’t be so naive thinking you know the roles and responsibilities of your key stakeholders during the incident.

Additionally, a method of communication needs to be established to enable rapid response. You must consider that your usual communication channels may be compromised, and the attacker may be listening to them. That is if you can even still gain access to them at all.


## 2. Critical asset identification 💎
 
During an attack, you must already understand your organisation's critical assets and where they are. This way, you can determine the scope and impact of the attack and direct where your security team needs to focus their efforts during the remediation stages of your incident response plan, minimising disruption to your business.

 
## 3. Testing your reflexes 🏃
 
Incident response should be treated like a reflex, and like any other reflex, if you don’t exercise them enough, they get slow, or you lose them entirely. While it can be challenging to replicate the intense pressure your team will endure throughout an actual breach, simulations and purple team exercises ensure a more tightly coordinated and prepared team for when a real incident occurs. 

Whatever exercises you choose to do, ensure that you spice things up and don’t end up running the same scenario every 12 months - you don’t go to the gym to train the same muscle every day. You must involve various business stakeholders (such as PR, Finance, etc.) to ensure that they are prepared and know exactly what role they have to play.

Some common scenarios include: 
* High-priority/crown jewel compromise
* Successful data breach
* Ransomware attempt detected
* Active adversary within the network

It might also be useful to perform positive and false positive scenarios.

 
## 4. Detective and protective tooling 🧭
 
Although attacks and breaches are inevitable, that doesn’t mean you shouldn’t implement the right tools to detect and protect against cyber attacks. The best way to deal with an incident is to protect against it in the first place. 

## 5. Visibility maximisation 👀
 
You want to ensure that you and your team have maximum visibility of your technical estate. Without it, you won’t be able to determine what is happening during an attack and you will struggle to respond appropriately. It is mind-boggling to think about how many organisations don’t have visibility of their assets. 

So, before an attack occurs, your organisation's security and IT teams need to work together to ensure they have total visibility to truly understand the scope of an attack, including determining the entry point of your threat actor(s) and points of persistence. Total visibility includes, but is not limited to, the collection of log data from all your devices, focusing on user endpoints and network data. This typically means implementing a log aggregation or Security Information Events Management (SIEM) solution along with deploying endpoint agents to collect the logs. 

Since most attacks take days or weeks to discover, keeping hold of historical event data going back weeks or months (even up to a year) is important so that your incident response team can access and audit the information during an investigation. You should also ensure that these logs are stored safely, securely, and backed up. If a threat actor is aware that you have such a solution in place, they will certainly attempt to compromise the integrity of the logs to cover their tracks. Additionally, these logs give away a lot of information about your network architecture, the tools and services your organisation uses and more. It's a treasure trove of information, so make sure it’s kept secure!

## 6. IAM implementation 🔑

Attackers will try to leverage weak access controls to infiltrate your organisation and escalate their privileges. Your security team should regularly audit and review the organisation's access controls to ensure they have been implemented correctly and are up-to-date. This audit should also include: 
* The deployment of multi-factor authentication where appropriate. 
* Using the principle of least privilege to ensure that users only have access to the essential assets and services they need to perform their role. In addition, it would limit the number of administrator accounts.
*Changing default passwords.
* Reducing the number of assets/access points you need to monitor by decommissioning unnecessary or unused assets and access points.


## 7. Invest in your investigation tooling 🧰

Once your organisation has nailed down and ascertained maximum visibility, you should also invest in the right investigatory tooling to enable your incident response team to provide the necessary context during an investigation. These tools don’t have to cost the earth either, and in some cases, can be supplemented with well-maintained open-source ones.

Some of the most common tools used in incident response include endpoint detection and response (EDR) or extended (XDR), which allow you to hunt across your environment for indicators of compromise (IOCs). EDR tools help analysts pinpoint which assets have been compromised, enabling them to determine the scope of the attack in turn.

The more data is collected, the more context is available and the better the picture we can paint. Having broad visibility by collecting event data from network devices, endpoints and more should enable your analysts to determine not only what the attackers were targeting but also how and where they gained initial access to your environment. They can also understand whether or not the attackers still have the ability to gain access using persistence methods.

There is a wide array of tools that may be helpful to your security team and, in particular, your incident response team, which will be discussed in another article at another time. However, here is a key headline - **it’s important to ensure your team has access to the right tools.**


## 8. Create an action plan 🏗️

Detection (although very important) is just one piece of the incident response puzzle. To appropriately respond to an attack, your IT and security teams must collaborate to ensure they can conduct a wide range of remedial actions to disrupt and neutralise the threat. This action plan, sometimes referred to as a playbook, can often include data collection and examination steps to determine the right actions to thwart the attacker efficiently. Different playbooks might be used for dealing with different types of attacks. Response actions typically include, but are not limited to: 

* Isolating the infected hosts. 🧟
* Blocking access to command and control (C2) services. 🛑
* Blocking malicious website activity. 
* Blocking malicious files, processes and programs. 
* Freezing compromised user accounts. ❄️
* Closing the entry points the attacker used to obtain access. 🔐
* Closing or isolating areas of persistence.
* Collecting and cleaning up adversary artefacts and tools (this includes malicious files the attacker might have left or broken the integrity of). 👨‍💻
* Adjusting your configurations (updating your firewall policies and EDR tools to identify and prevent similar attacks in the future).
* Restoring impacted assets to health. 🩹


## 9. Awareness training 🧠

As it’s often the case, the user is the weakest link in your organisation. While no training program will ever be 100% effective against the most cunning and determined adversary, education programs help reduce risk and potentially the number of alerts your security team should manage. But make sure the training is as engaging as it is informative and doesn’t lead down the trail to scaremongering. Remember, you still want effective employees!

Phishing simulations using tools such as (GoPhish) [https://getgophish.com/] provide a safe way for your staff to experience phishing and enable your security team to identify risky user groups who may require additional training. 


## 10. Resource for combat 🔫

Having the right people with the right training and experience is crucial to ensuring your organisation’s success in combating and thwarting the adversary. However, finding the right people with the right training is sometimes easier said than done. Currently, the talent pool within the cybersecurity industry is a hot topic, with many opinions from “the pool isn’t big enough for the demand” to “AI will take our jobs”. Hundreds of programmes are also available for those looking to retrain in a new industry, with veteran programmes spouting £70k salaries on average and the more traditional CompTIA, isc2 certification routes.

It’s important you make the right decision for your business, whether promoting within, scaling out or hiring a managed security service. Many organisations are not equipped to handle incidents on their own. Swift and effective incident response requires having access to resources with experience. Carefully consider your options to ensure that you can properly respond to whatever incidents come your way. 

Managed Detection and Response (MDR) services are a popular option for many reasons, one of the most prominent being offsetting risks. MDR providers typically offer 24/7 threat hunting, investigation, and incident response, all rolled into a single package. They not only help your organisation respond to threats but also typically provide risk assessment services with mitigation or hygiene workbooks to reduce the likelihood of an incident in the first place. 

Digital Forensic Incident Response (DFIR) services are also occasionally retained after an incident to collect evidence for supporting legal or insurance claims. 


## In conclusion

When facing a cybersecurity incident, it is essential to handle it as quickly and efficiently as possible - time is of the essence! Having an incident response plan that is well-prepared, well-understood, and immediately actionable will dramatically reduce the impact of an attack on your organisation. 

Hopefully, this write-up will help you on your journey to implementing or improving your incident response plan. If you have any further questions or require support in writing your plan, please feel free to leave a comment or reach out to me on LinkedIn. 

Stay cyber-safe!
