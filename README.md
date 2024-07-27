<h1> Lesson 10.2: Reconnaissance and Social Engineering</h1>
<h2> Summary</h2>

<p1>This lesson introduces students to reconnaissance and social engineering, which are the initial stages of a cyber attack. While reconnaissance involves gathering information without direct interaction with the target, social engineering manipulates individuals to divulge confidential information or perform specific actions. Understanding these techniques is crucial for identifying and defending against them.</p1>
<br>

<h2>Learning Objectives</h2>
<ul>
<li>Understand the distinction between reconnaissance and direct cyber-attacks.</li>
  <br>
<li>Recognize various methods used in social engineering and their purposes.</li><br>
  
<li>Identify potential threats in everyday scenarios.</li><br>

<li>Develop strategies to protect oneself and one's organization from social engineering attacks.</li><br>

<li>Analyze real-world examples to understand their impact and countermeasures.</li>
</ul>


<h2>Vocabulary and Acronyms</h2>

<ul>
<li>

  **Reconnaissance**</li>
  
<li>

**Phishing**</li>
  
<li>
  
**Social Engineering**</li>
  
<li>
  
**Spear Phishing**</li>
  
<li>
  
  **Pretexting**</li>
  
<li>
  
 **Vishing**</li>

  <li>
  
 **Dumpster Diving**</li>

 <li>
  
 **Tailgating**</li>

</ul>

<h2>NICE Framework KSAs</h2>

<ul>
<li>K0119: Knowledge of hacking methodologies.</li>
<br>
<li>K0206: Knowledge of ethical hacking principles and techniques.	</li>
<br>
<li>K0177: Knowledge of cyber attack stages (e.g., reconnaissance, scanning, enumeration, gaining access, escalation of privileges, maintaining access, network exploitation, covering tracks).</li>
<br>
<li>K0005: Knowledge of cyber threats and vulnerabilities. </li>
<br>
<li>K0009: Knowledge of application vulnerabilities.</li>
<br>
<li>K0144: Knowledge of social dynamics of computer attackers in a global context.</li>
<br>
<li>S0052: Skill in the use of social engineering techniques. (e.g., phishing, baiting, tailgating, etc.).</li>
<br>
</ul>



<h2>Lesson Prerequisites</h2>
<p1>Any topical or subject matter to prepare for the lesson. In Advanced Cyber Lessons, previous Lessons can be referenced. </p1>
<br>


<h2>Introduction</h2>

Today, we will delve into the intriguing world of Reconnaissance and Social Engineering in cybersecurity.
<ul>
<li>
  
**Reconnaissance:** </li>
<ul>
  <li>Before attackers launch a direct attack, they often gather preliminary data or intelligence on their target. This act is called reconnaissance. Think of it as the blueprint-gathering phase of a heist. Before an attacker launches a direct attack, they often gather preliminary data or intelligence on their target. This act is called reconnaissance. Think of it as the blueprint-gathering phase of a heist.</li>
</ul>

<li>
  
**Social Engineering:** </li>
<ul>
<li>Imagine manipulating someone to hand you the blueprint instead of stealing it. That's social engineering. It’s less about cracking codes and more about managing human behavior. Now, imagine using someone. Have you ever sent the blueprint instead of stealing it? That's essentially social engineering. It’s less about cracking codes and more about controlling human behavior.</li>
</ul>
</ul>

<h4><ins>
  
**Real-world examples of Social Engineering:** </ins></h4>
<ul>
  <li>
    
  **Phishing:** 
  <ul><li>We’ve all received emails claiming we’ve won a considerable sum of money or warning us of an account breach urging us to click on a link. This is a classic example of phishing. One notable instance occurred in 2016 when a Lithuanian man scammed Facebook and Google out of more than $100 million by sending fake emails that appeared to be legitimate invoices for their services.</li></ul>
  <li>
    
  **Spear Phishing:** 
  <ul><li>This is a more targeted form of phishing. In 2011, RSA, a major security company, was compromised when an employee opened a spear-phishing email that appeared to be a legitimate recruitment plan.</li></ul>
  <li>
    
  **Vishing:** 
  <ul><li>Voice phishing or "vishing" involves a call from "your bank" asking you to verify your details due to suspicious activity. In 2019, a tech journalist recorded a vishing attempt where scammers posed as Apple Support, trying to steal iCloud credentials.</li></ul>
  <li>
  
  **Pretexting:** 
  <ul><li>The scammer creates a fabricated scenario to obtain information. A famous case involved Hewlett Packard's boardroom scandals in 2006, where investigators posed as individuals to obtain phone records.</li></ul>
  <li>
    
  **Tailgating:** 
  <ul><li>Have you ever held a door for someone at your workplace? You might have inadvertently let in an attacker. In various instances, attackers gain physical access to a facility this way.</li></ul>
  <li>
    
  **Dumpster Diving:** 
  <ul><li>While it might sound unappealing, scavenging through trash has yielded sensitive information for attackers.</li></ul>
</ul>



<h4><ins>
  
**Countermeasures:** </ins></h4>
<ul>

<li>
  
**Education and Training:** Forewarned is forearmed. Regularly updating staff and individuals about attackers' latest techniques can mitigate risks.</li>
<li>
  
**Two-factor Authentication:** Even if someone has your password, they won't have the unique code sent to your mobile device or email.</li>
<li>
  
**Regularly Update Software:** Many phishing attempts exploit vulnerabilities in outdated software.</li>
<li>
  
**Verify Unexpected Communications:** If your bank calls you, hang up and call them back on their official number.</li>

</ul>


<h2>Reconnaissance in Ethical Hacking</h2>

Reconnaissance, often referred to as the "information gathering" phase, is the initial step in both ethical hacking and malicious hacking. Its inclusion in ethical hacking is crucial for several reasons:

<ul>
  <li>
    
  **Replicating Real-World Attacks:** 
  <ul><li>Ethical hackers aim to mimic the methods and techniques of malicious hackers. By undergoing the reconnaissance phase, they can accurately replicate the steps an adversary would take, allowing organizations to understand potential vulnerabilities better.</li></ul>
  <li>
    
  **Identification of Vulnerabilities:** 
   <ul><li>Ethical hackers use reconnaissance to gather as much information about their target as possible, helping them identify weak points in systems or processes. This information is invaluable for organizations to strengthen their defenses.</li></ul>
  <li>
    
  **Enhancing Efficiency of Later Stages:** 
   <ul><li>A thorough reconnaissance phase ensures that subsequent hacking stages, like exploitation or post-exploitation, are executed more efficiently. With ample information, ethical hackers can strategize their tests better.</li></ul>
   <li>
     
  **Avoiding Unnecessary Disruptions:** 
   <ul><li>Ethical hacking aims to find vulnerabilities without causing undue disturbance to the target system. By gathering relevant information beforehand, ethical hackers can ensure they target suitable systems and avoid causing unintended damage or disruptions.
</li></ul>
  
</ul>


<h2>Tools Used for Reconnaissance and Social Engineering</h2>

<ul>
   <li><ins>NMAP</ins></li>
  <ul>
    <li>A versatile tool used to discover devices running on a network and find open ports along with various network attributes.</li>
  </ul>
  <br>
   <li><ins>Shodan</ins></li>
  <ul>
    <li>Often referred to as the "search engine for devices," it can find devices connected to the internet, from servers to refrigerators.</li>
  </ul>
   <br>
   <li><ins>theHarvester</ins></li>
  <ul>
    <li>Used for gathering emails, subdomains, hosts, employee names, open ports, and banners from different public sources.</li>
  </ul>
   <br>
   <li><ins>Maltego</ins></li>
  <ul>
    <li>A tool for graphical link analyses that can uncover relationships and links between people, companies, websites, domains, etc.</li>
  </ul>
   <br>
   <li><ins>Metasploit</ins></li>
  <ul>
    <li>While it's more than just a reconnaissance tool, it comes with modules that can be used for information gathering.</li>
  </ul>
   <br>
   <li><ins>Social-Engineer Toolkit (SET)</ins></li>
  <ul>
    <li>Specifically designed for social engineering attacks, it offers various customizable attack vectors, including spear-phishing emails and malicious QR codes.</li>
  </ul>
   <br>
   <li><ins>Phishing Frenzy</ins></li>
  <ul>
    <li>An open-source Ruby on Rails application used to manage email phishing campaigns.</li>
  </ul>
   <br>
   <li><ins>GoPhish</ins></li>
   <ul>
    <li>Offers the ability to simulate real-world phishing attacks against an organization and evaluate the readiness of its employees.
</li>
  </ul>
  
</ul>


<h2>Conclusion</h2>
While technology has vulnerabilities, humans can be the weakest link in the security chain. By understanding these tactics, we can better defend against them. Stay alert, stay skeptical, and stay safe. While reconnaissance is the initial phase of an attack, it's a foundational step for ethical hackers. By understanding and replicating the methods adversaries use to gather information, ethical hackers provide organizations with invaluable insights into their security posture, enabling them to strengthen their defenses and safeguard against genuine threats.

<h2>Definitions</h2>
<ul>
<li><b>Reconnaissance:</b> The process of gathering information about a target to identify potential vulnerabilities and plan an attack.</li><br>
<li><b>Phishing:</b>  A fraudulent attempt to obtain sensitive information by masquerading as a trustworthy entity through email or other communication methods.</li><br>
<li><b>Social Engineering:</b>  The manipulation of individuals into divulging confidential information or performing actions that compromise security.</li><br>
<li><b>Spear Phishing:</b>  A targeted phishing attack aimed at a specific individual or organization, often using personalized information to increase the likelihood of success.</li><br>
<li><b>Pretexting:</b>  A form of social engineering where an attacker creates a fabricated scenario to obtain sensitive information from a victim.</li><br>
<li><b>Vishing:</b>  Voice phishing, where attackers use phone calls or voice messages to trick individuals into revealing confidential information.</li><br>
<li><b>Dumpster Diving:</b>  The act of searching through discarded materials, such as trash or recycling, to find sensitive or useful information that can aid in an attack.</li><br>
<li><b>Tailgating:</b>  The practice of gaining unauthorized access to a secure area by following closely behind an authorized individual, often without proper credentials.</li>
</ul>


<h2> Presentation</h2>
<a href="https://docs.google.com/presentation/d/15nsaywNGeBfh6nksZhc9GlR1ZE7CuUw4/edit?usp=sharing&ouid=110228847857413878764&rtpof=true&sd=true"> Cyber Ethics </a>


<h2> Hands-On Labs</h2>

<a href ="https://docs.google.com/document/d/1xyCrw8crtcdxCTVzZLfDrcThbkjGJjJcP7KIvldk4uI/edit?usp=sharing"> Cyber Ethics Activity </a><br>
<br>
<a href="https://docs.google.com/document/d/1BLvrFPza5NSXWf9I6OAfzUShpFwHzYx4rJ41UXCp0Yg/edit?usp=sharing"> Cyber Ethics Group Discussion </a>

<h2> Games</h2>

<h2>Additonal Resources</h2>
