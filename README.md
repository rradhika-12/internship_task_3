# internship_task_3
## Basic Vulnerability Scan on PC

### Objective: Use free tools to identify common vulnerabilities on your computer.
Tools: OpenVAS Community Edition (free vulnerability scanner) or Nessus Essentials.
### Deliverables: Vulnerability scan report with identified issues.    

# Tool used: Nessus 

    Step 1: Install Nessus Essentials from https://www.tenable.com/products/nessus/nessus-essentials 
    Step 2: Register with your email to get a free activation code.
    Step 3: After installation, go to localhost in your browser.
    Step 4: Enter your activation code send to email ID and create an admin account.
    Step 5: Go to “Scans” → Click “New Scan”
    Step 6: Choose “Basic Network Scan” template.
    Step 7: Name your scan.
    Step 8: Enter your local IP in the Target field.
    Step 9: Save and click “Launch”.
    Step 10: Do not interrupt the scan. Ensure stable internet and power if possible. Once the scan finishes, check the results.
        High/Medium/Low severity vulnerabilities.
        Common issues: Open ports, weak SSL/TLS, outdated software, default passwords, etc.
        Click on each vulnerability for a detailed explanation and recommended fixes.
        Document/report of scan can also be downloaded.

  Here in this task for identifying vulnerabilities in own system, I used 2 IP (System and Kali Linux) using Nessus Essentials.
  Nessus Essentials is a free vulnerability scanning tool offered by Tenable. It's designed for students, beginners, and security enthusiasts to learn how to scan systems for weaknesses. 
  ##Scan types: 	Full vulnerability scan, basic network scan, web application scan, and more + Access to thousands of vulnerability checks (CVEs) + 	Clean, detailed, exportable reports (PDF, HTML, CSV).
  ##What It Can Detect:
  
                Outdated software (e.g., old versions of Windows, browsers, services)
                Open and vulnerable ports
                Weak passwords
                Misconfigurations (e.g., insecure services enabled)
                Publicly known vulnerabilities (via CVEs)

###All the findings and vulnerability scannings screenshots are attached in this repository.
 
