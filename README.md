# Adversarial-Resilience-Assessing-Infrastructure-Security


![Minion](https://video.udacity-data.com/topher/2020/October/5f88a955_noun-defense-1645323/noun-defense-1645323.png)
## Scenario
**Adversarial Resilience - Assessing StaticSpeed's Infrastructure Security Posture Report**

Your employer, NuttyUtility, is a company in the technology sector with cutting edge software that is known to be targeted by foreign adversaries and has recently acquired a new company, StaticSpeed. Your job is to assess the security posture of the newly acquired company.

Specifically, your boss wants to know the current status of assets inside the perimeter (desktops, servers, remote access, firewalls, applications). Use the given information about the systems currently in place to understand better the possible vulnerabilities and exposures at this new company.

Upon an initial inspection as part of the acquisition, we suspect these systems have not been kept up to date. There is a likelihood that the servers and desktops at this location are running vulnerable applications and misconfigurations that may lead to compromises either by rogue insiders or external malicious actors. If this is the case, this would be an unacceptable scenario as we plan to combine StaticSpeeds systems with our extended network.

Your goal is to establish what assets are in place, perform a security assessment based on industry security controls and best practices, and execute a vulnerability assessment against servers and desktop assets. The result of this assessment will be a report that you must present to your stakeholders. They will relay your findings to the infrastructure team. Together they will decide if this new company is ready to be integrated or if appropriate controls and mitigations need to be in place before this happens.

## Report Criteria 
### Asset Identification

```
Identify the sources of Industry vulnerability and security control frameworks.
```

```
Verify the current setting of software updates and third-party packages at audited machines.
```
```
Verify that native protections for the operating systems are in place.
```
```
Use NMAP to correctly identify all live hosts in a network.
```

### Assess Access Management

```
Check for current settings on network segmentation, VLANs, Domain Isolation, or IP Security Policies.
```
```
Investigate and find Remote Access Services, Protocols, and if the IPv6 protocol is running.
```
```
Find and verify if firewalls are set and recommend what ports should be open for
business and network operations.
```
```
Identify and mitigate user privilege Issues.
```

### Log Monitoring Setup for Detection at Targeted Assets

```
Use Wireshark or tcpdump to perform traffic inspection and investigation.
```
```
Use Wireshark or tcpdump analyze a successful attack (Lateral Movement Mitre ATT&CK TA0008)
```
```
Use logs at audited machines to find login failures and suspicious access attempts.
```
```
Verify that the systems are logging correctly.
```

### Assess Authentication Management

```
Verify what type of authentication and access controls are in place for privileged and unprivileged users.
```
```
Audit password policies in Windows & Linux.
```
```
Verify the use of strong encryption in audited systems.
```
```
Audit network services passwords using NMAP NSE scripts.
```

### Vulnerability Report for Stakeholders

```
Produce a Vulnerability report following industry best practices for stakeholders.
```
