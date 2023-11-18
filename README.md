## Eternal Check 2.0

* Eternal Check verifies if an ip is vulnerable to the smb vulnerabilities 
- Eternal Blue 
- Eternal Romance 
- Eternal champion 
- Eternal synergy
- Erraticgopher SMB v1 Exploit (Windows XP & Server 2003)
- Eagerlever SMB v1 Exploit (Windows XP & 2000)

# Screenshots
<img src="https://s22.postimg.cc/ypjtt6wfl/echeck20.png" width="55%"></img>
* <img src="https://s22.postimg.cc/6pfq90nv5/echeck2-2003.png" width="25%"></img><img src="https://s22.postimg.cc/v5xw3i41d/echeck2.png" width="25%"></img><img src="https://s22.postimg.cc/n1udc79hd/echeck2b.png" width="25%"></img>

# Added in 2.0
* Architouch (uses port 49152 "In case opened" in remote ip to retrieve OS architecture)
* RpcTouch (uses also SMB port to retrieve OS version)

# Eternal Check Running (Video)
* Eternal Check 1.0 : https://www.youtube.com/watch?v=rQBCELDPiok
* Eternal Check 1.1 : https://www.youtube.com/watch?v=SqIBmAx-Llg

# Requirements

* nmap
* winbind
* wine32 
* wget

* Aditional info in how to install wine 32bit on a 64bit machine :
https://wiki.debian.org/Wine to know how to install wine32 on a 64bit machine

# Usage

* example 1 : ./echeck 
* example 2 : ./echeck 192.68.2.56

# Important
* Do not expect much support or any at all 

# Last Notes (References of these vulnerabilities)

* Erraticgopher smb v1 https://www.vulnerabilitycenter.com/#search=CVE-2017-8461
* https://blogs.forcepoint.com/security-labs/evasions-used-shadow-brokers-tools-danderspritz-and-doublepulsar-part-2-2
* https://blogs.technet.microsoft.com/srd/2017/07/13/eternal-synergy-exploit-analysis/
* https://blogs.technet.microsoft.com/srd/2017/06/29/eternal-champion-exploit-analysis/
* https://en.wikipedia.org/wiki/EternalBlue

# Last version 1.1
* https://gitlab.com/peterpt/eternal_check/tree/Eternal_Check-1.1
