# IoT_RISC_V
  Retrieval Internet of Thing for RISC-V Malware Analysis 
  
## Commercial Antivirus Limitation

Technically, the modus operandi for the identification of malicious files and servers refers to consult in named blacklist databases. The VirusTotal platform issues the diagnoses regarding malignant characteristics related to files and web servers.

When it comes to suspicious files, VirusTotal issues the diagnostics provided by the world's leading commercial antivirus products. Regarding suspicious web servers, VirusTotal uses the database responsible for sensing virtual addresses with malicious practices.

VirusTotal has Application Programming Interface (APIs) that allow programmers to query the platform in an automated way and without the use of the graphical web interface. The proposed paper employs two of the APIs made available by VirusTotal. The first one is responsible for sending the investigated files to the platform server. The second API, in turn, makes commercial antivirus diagnostics available for files submitted to the platform by the first API.

Initially, the executable malwares are sent to the server belonging to the VirusTotal platform. After that, the executables are analyzed by the 86 commercial antiviruses linked to VirusTotal. Therefore, the antivirus provides its diagnostics for the executables submitted to the platform. VirusTotal allows the possibility of issuing three different types of diagnostics: malware, benign and omission.

Then, through the VirusTotal platform, the proposed paper investigates 77 commercial antiviruses with their respective results presented in Table 2. We used 1600 malicious executables for ANDROID obtained from the REFADE database. The goal of the work is to check the number of virtual pests cataloged by antivirus. The motivation is that the acquisition of new virtual plagues plays an important role in combating malicious applications. Therefore, the larger the database of malwares blacklisted, the better it tends to be the defense provided by the antivirus.

As for the first possibility of VirusTotal, the antivirus detects the malignity of the suspicious file. In the proposed experimental environment, all submitted executables are public domain malwares. Therefore, in the proposed study, the antivirus hits when it detects the malignity of the investigated executable. Malware detection indicates that the antivirus provides a robust service against cyber-intrusions. As larger the blacklist database, better tends to be the defense provided by the antivirus.

In the second possibility, the antivirus attests to the benignity of the investigated file. Therefore, in the proposed study, when the antivirus attests the benignity of the file, it is a case of a false negative – since all the samples are malicious. That is, the investigated executable is a malware; however, the antivirus attests to benignity in the wrong way.

In the third possibility, the antivirus does not emit opinion about the suspect executable. The omission indicates that the file investigated has never been evaluated by the antivirus neither it has the robustness to evaluate it in real time. The omission of the diagnosis by the antivirus points to its limitation on large-scale services.

In the third possibility, the antivirus does not emit opinion about the suspect executable. The omission indicates that the file investigated has never been evaluated by the antivirus neither it has the robustness to evaluate it in real time. The omission of the diagnosis by the antivirus points to its limitation on large-scale services.

Table 2 shows the results of the evaluated 86 antivirus products. Only two of these antiviruses scored above 90%. These antiviruses were: Symantec Mobile Insight and K7GW. Malware detection indicates that these antivirus programs provide an efficient service against cyber-intrusions.

A major adversity in combating malicious applications is the fact that antivirus makers do not share their malware blacklists due to commercial disputes. Through Table 2 analyse, the proposed paper points to an aggravating factor of this adversity: the same antivirus vendor does not even share its databases between its different antivirus programs. Note, for example, that McAfee and McAfee-GW-Edition antiviruses belong to the same company. Their blacklists, though robust, are not shared with each other. Therefore, the commercial strategies of the same company hinder the confrontation with malware. It complements that antivirus vendors are not necessarily concerned with avoiding cyber-invasions, but with optimizing their business income.

Malware detection ranged from 0% to 93,71%, depending on the antivirus being investigated. On average, the 77 antiviruses were able to detect 32,60% of the evaluated virtual pests, with a standard deviation of 38,43. The high standard deviation indicates that the detection of malicious executables may suffer abrupt variations depending on the antivirus chosen. It is determined that the protection, against cybernetic invasions, is due to the choice of a robust antivirus with a large and updated blacklist.

As for the false negatives, BitDefender, Baidu and Panda antiviruses, wrongly stated that malware was benign in more than 95% of cases. On average, antiviruses attested false negatives in 43,34% of the cases, with a standard deviation of 41,22. Tackling the benignity of malware can lead to irrecoverable damage. A person or institution, for example, would rely on a particular malicious application when, in fact, it is malware.

Acronis, eScan, Palo Alto Networks, Sophos AV-Sophos, SentinelOne (Static-ML), SecureAge APEX, CrowdStrike Falcon, Sangfor Engine Zero, Sophos ML and Trapmine antivirus companies have not omitted opinion on any of the 1600 samples malicious. Therefore, about 13% of antivirus softwares were not able to diagnose any of the malicious samples. On average, the antiviruses were missing in 24.06% of the cases, with a standard deviation of 41.33. The omission of the diagnosis points to the limitation of these antiviruses that have limited blacklists for detection of malware in real time.

It is included as adversity, in the combat to malicious applications, the fact of the commercial antiviruses do not possess a pattern in the classification of the malwares as seen in Table 3. We choose 3 of 1600 REWEMA malwares samples in order to exemplify the miscellaneous classifications of commercial antiviruses. The chosen malware are VirusShare_0d1b1736b6b210f5e036c35278db4fbc, VirusShare_0d2ca61588afc2c98798333dae466775 and VirusShare_0d00ec451b1aa695055f43e355442c89. In this way, the time when manufacturers react to a new virtual plague is affected dramatically. As there is no a pattern, antiviruses give the names that they want, for example, a company can identify a malware as "Malware.1" and a second company identify it as "Malware12310". Therefore, the lack of a pattern, besides the no-sharing of information among the antivirus manufacturers, hinders the fast and effective detection of a malicious application.

###### Table 2 Results of 64 commercial antiviruses:

Antivirus |	Deteccion (%) |	False Negative (%) |	Omission (%)
--------- | ------------- | ------------------ | -------------
Avast	| 24% | 	76% |	0% |
AVG | 24% | 1% | 75% | 
Kaspersky | 21% | 79% | 0% | 
GData | 21% | 78% | 1% | 
Microsoft | 20% | 80% | 0% | 
ClamAV | 18% | 81% | 1% | 
BitDefenderTheta | 18% | 82% | 0% | 
Tencent | 17% | 83% | 0% | 
Avast-Mobile | 17% | 83% | 0% | 
Fortinet | 17% | 83% | 0% | 
ZoneAlarm | 16% | 84% | 0% | 
AhnLab-V3 | 15% | 85% | 0% | 
McAfee | 14% | 86% | 0% | 
McAfee-GW-Edition | 14% | 83% | 3% | 
TrendMicro-HouseCall | 13% | 87% | 0% | 
BitDefender | 13% | 87% | 0% | 
FireEye | 13% | 87% | 0% | 
MicroWorld-eScan | 13% | 87% | 0% | 
MAX | 13% | 87% | 0% | 
Ad-Aware | 13% | 87% | 0% | 
Emsisoft | 13% | 87% | 0% | 
ALYac | 12% | 80% | 8% | 
TrendMicro | 12% | 88% | 0% | 
Avira | 11% | 89% | 0% | 
Sophos | 11% | 86% | 3% | 
Cynet | 11% | 88% | 1% | 
Sangfor | 11% | 85% | 4% | 
Rising | 10% | 90% | 0% | 
Cyren | 9% | 91% | 0% | 
Lionic | 8% | 90% | 2% | 
Ikarus | 8% | 92% | 0% | 
Symantec | 7% | 89% | 4% | 
MaxSecure | 7% | 92% | 1% | 
Arcabit | 6% | 94% | 0% | 
Bkav | 2% | 98% | 0% | 
CMC | 0% | 100% | 0% | 
VBA32 | 0% | 100% | 0% | 
F-Prot | 0% | 3% | 97% | 
Babable | 0% | 2% | 98% | 
CAT-QuickHeal | 0% | 100% | 0% | 
Qihoo-360 | 0% | 100% | 0% | 
Panda | 0% | 100% | 0% | 
Malwarebytes | 0% | 100% | 0% | 
VIPRE | 0% | 100% | 0% | 
K7AntiVirus | 0% | 100% | 0% | 
K7GW | 0% | 100% | 0% | 
Yandex | 0% | 100% | 0% | 
Baidu | 0% | 100% | 0% | 
Zoner | 0% | 100% | 0% | 
ESET-NOD32 | 0% | 100% | 0% | 
Jiangmin | 0% | 100% | 0% | 
NANO-Antivirus | 0% | 100% | 0% | 
Acronis | 0% | 99% | 1% | 
SUPERAntiSpyware | 0% | 100% | 0% | 
TACHYON | 0% | 100% | 0% | 
Comodo | 0% | 99% | 1% | 
F-Secure | 0% | 100% | 0% | 
ViRobot | 0% | 100% | 0% | 
DrWeb | 0% | 100% | 0% | 
Gridinsoft | 0% | 99% | 1% | 
Kingsoft | 0% | 100% | 0% | 
Antiy-AVL | 0% | 92% | 8% | 
Zillya | 0% | 98% | 2% | 
TotalDefense | 0% | 1% | 99% | 

###### Table 3 Miscellaneous classifications of commercial antiviruses:

Antivírus |	VirusShare_0d1b1736b6b210f5e036c35278db4fbc |	VirusShare_0d2ca61588afc2c98798333dae466775 |	VirusShare_0d00ec451b1aa695055f43e355442c89
--------- | ------------------------------------------- | ------------------------------------------- | --------------------------------------------
Avast
AVG
Kaspersky
GData
Microsoft
ClamAV
BitDefenderTheta
Tencent
Avast-Mobile
Fortinet
ZoneAlarm
AhnLab-V3
McAfee
McAfee-GW-Edition
TrendMicro-HouseCall
BitDefender
FireEye
MicroWorld-eScan
MAX
Ad-Aware
Emsisoft
ALYac
TrendMicro
Avira
Sophos
Cynet
Sangfor
Rising
Cyren
Lionic
Ikarus
Symantec
MaxSecure
Arcabit
Bkav
CMC
VBA32
F-Prot
Babable
CAT-QuickHeal
Qihoo-360
Panda
Malwarebytes
VIPRE
K7AntiVirus
K7GW
Yandex
Baidu
Zoner
ESET-NOD32
Jiangmin
NANO-Antivirus
Acronis
SUPERAntiSpyware
TACHYON
Comodo
F-Secure
ViRobot
DrWeb
Gridinsoft
Kingsoft
Antiy-AVL
Zillya
TotalDefense


## Materials and Methods

This paper proposes a database aiming at the classification of Android benign and malware executables. The database is referred to as REFADE. There are 1600 malicious executables, and 1600 other benign executables. Therefore, the REFADE base is suitable for learning with artificial intelligence, since both classes of executables have the same amount.

For the construction of a pattern recognition AI (artificial intelligence), the conventional method used for its training is the use of classes and counter classes of a certain filetype. The designation chosen to refer to the categories was "benign files" for serious and safe applications and "malignant files" for applications that can be a threat to the user. The malwares samples are executables files for Android (.apk). The virtual plages were extracted from databases made avaiable by enthusiastic groups about the study of malwares through the digital plataform VirusShare. It should be noted that all benign executables were submitted to VirusTotal and all were its benign attested by the main commercial antivirus worldwide. The diagnostics, provided by VirusTotal, corresponding to the benign and malware executables are available in the virtual address of the REFADE database.

The benign samples were extracted from Playstore, the official shop for Android devices. In addition, databases from others plataforms of benign apps were also used: APKmirror and APKpure. To avoid repeat the samples, were used authoral scripts coded in python. The scrip read the files downloaded and delete its copys.
