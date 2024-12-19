# Incident report analysis

> [!NOTE]
> This exercise is a component of the [Google Cybersecurity Professional Certificate](https://www.coursera.org/professional-certificates/google-cybersecurity) program. It's designed as a simulated scenario to solidify my understanding of Network Analysis.

## Activity Overview
In this activity, you will create an incident report using the knowledge you’ve gained about networks throughout this course to analyze a network incident. You will analyze the situation using the National Institute of Standards and Technology's Cybersecurity Framework (NIST CSF). The CSF is a voluntary framework that consists of standards, guidelines, and best practices to manage cybersecurity risk. Creating a quality cybersecurity incident report and applying the CSF can demonstrate a proactive approach to security, improving communication and transparency with stakeholders, and improve security practices within your organization. You can also add the incident report you create to your cybersecurity portfolio when  you complete it.

The CSF is scalable and can be applied in a wide variety of contexts. As you continue to learn more and refine your understanding of key cybersecurity skills, you can use the templates provided in this activity in other situations. Knowing how to identify which security measures to apply in response to business needs will help you determine which are the best available options when it comes to network security.

## Scenario
You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

1. A new firewall rule to limit the rate of incoming ICMP packets

2. Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

3. Network monitoring software to detect abnormal traffic patterns

4. An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity event and integrate your analysis into a general security strategy. 

# Incident report analysis
| Summary | The company experienced a DDoS attack, which compromised the internal network for two hours until it was resolved. The organization’s network services stopped responding due to an incoming flood of ICMP packets through an unconfigured firewall. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. |
|---|---|
| **Identify** | The attack exploited an unconfigured firewall, allowing a flood of ICMP packets to overwhelm the entire internal network. This caused significant congestion, rendering critical applications and services inaccessible. Business processes, including web design, graphic design, social media marketing, and client communication, were disrupted. Employees, including IT staff, design teams, marketing teams, and management, were affected as they lost access to essential systems. |
| **Protect** | The cybersecurity team implemented a new firewall rule to limit the rate of incoming ICMP packets and an IDS/IPS system to filter out ICMP traffic based on suspicious activities. |
| **Detect** | The cybersecurity team implemented a source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packet, and also started using a network monitoring software to detect abnormal traffic patterns. |
| **Respond** | For responding to similar attacks in the future, action plans should include procedures for isolating affected resources, communicating with IT staff and end users, and analyzing the cause and impact of the attack. |
| **Recover** | To recover from a DDoS attack by ICMP flooding, the affected systems have to be restored from backups and ensure network services are re-established. Firewalls should be reconfigured to block malicious traffic, and DDoS mitigation measures implemented to prevent future attacks. Communication is essential throughout the recovery process. Additionally, a post-incident review should assess vulnerabilities and strengthen protections. |


### Reflections/Notes: 

+ Conduct regular security audits to identify and patch vulnerabilities, such as unconfigured firewalls, that could be exploited by attackers. 
+ A capacitation for all the employees about the importance of cybersecurity, potential impact of attacks, and how to identify early warning indicators.







