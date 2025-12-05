<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <h1>Proof-of-Concept Exploits Repository<h1>
</head>
<body>
<p>
    This repository contains my own collection of proof-of-concept (PoC) exploits created for security testing and research purposes.
    Each folder is organized by CVE identifier (for example: <code>CVE-2025-XXXX/</code>), and inside you will find the corresponding exploit code and documentation.
</p>

<p>
    Some PoCs may also be available in ExploitDB, while others are exclusively maintained in this repository.
</p>

<h2>Purpose</h2>
<ul>
    <li>Provide reproducible PoCs to validate the impact of specific vulnerabilities.</li>
    <li>Support penetration testers and security researchers in controlled security assessments.</li>
    <li>Help organizations evaluate exposure across different technologies and environments.</li>
</ul>

<h2>Repository Structure</h2>

<pre>
/CVE-2025-XXXX/
    exploit.py

/CVE-2024-YYYY/
    exploit.sh
</pre>

<p>Each CVE folder typically includes:</p>
<ul>
    <li>Technical explanation of the vulnerability</li>
    <li>Impact analysis</li>
    <li>Affected versions</li>
    <li>Exploit or PoC code</li>
    <li>Steps to reproduce</li>
    <li>Mitigation recommendations when relevant</li>
</ul>

<h2>Disclaimer</h2>
<p>
    All content is provided strictly for educational and authorized security testing.
    Do not use these exploits on systems without explicit permission.
    The author is not responsible for misuse or unlawful activity.
</p>

<h2>Contributions</h2>
<p>
    Contributions and improvements are welcome. Please follow responsible disclosure practices when submitting new PoCs.
</p>

</body>
</html>
