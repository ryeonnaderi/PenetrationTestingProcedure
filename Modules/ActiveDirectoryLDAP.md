Active Directory service is a distributed heirarchical structure that includes
Domain Controller
Domain Users
Domain Group Information
Default Domain Policy
Domain Functional Levels 
Password Policy
Group Policy Objects
Kerberos Delegation
Domain Trusts
Access Control Lists


Many attacks exist that merely leverage AD misconfigurations, bad practices, or poor administration, such as:

Kerberoasting / ASREPRoasting
NTLM Relaying
Network traffic poisoning
Password spraying
Kerberos delegation abuse
Domain trust abuse
Credential theft
Object control



Active Directory Structure
arranged in a hierarchical tree structure with a forest at the top containing one or more domains or subdomains

Forest:

A forest is a security boundary within which all objects are under admin control

Forest contains domains

domain may contain further chidl or subdomains. 
A domain contains objects 
objects are the most basic units of data in AD

