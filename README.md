# Engenharia-Reversa-APK
Este conteúdo foi criado para Fins Educativos de Engenharia Reversa. 
No intuito de mostrar como inserir uma backdor em uma APK Original;
O objetivo da desta backdor, é dar para ao atacando o acesso ao celular da vitima, então após a vitima instalar 
a aplicação infectada o atacante vai conseguir o acesso via Man-In-The-Middle.
No entanto para esta demostração foi baixado a apk coronavirus-covid-19, onde através desta APK Original 
foi injetado Virus Malicioso e renomeado para Convit19_Grafico.apk para que possamos iniciar a 
analise de engenharia reversa.
Não instale o app Convit19_Grafico.apk

# Antivirus que detectou ameaça
AhnLab-V3                  Backdoor/Android.HiddenSploit.734097

Avast                      Android:Metasploit-Q [PUP]

Avast-Mobile Android:      Metasploit-Q [PUP]

AVG Android:               Metasploit-Q [PUP]

Avira (no cloud)           ANDROID/Dldr.Agent.PAF.Gen

DrWeb                      Android.RemoteCode.68

ESET-NOD32                 A Variant Of Android/TrojanDownloader.Agent.JN

F-Secure                   Malware.ANDROID/Dldr.Agent.BI.Gen

Fortinet                   Android/Agent.JN!tr

Kaspersky                  HEUR:Trojan-Downloader.AndroidOS.Masplot.a

ZoneAlarm by Check Point   HEUR:Trojan-Downloader.AndroidOS.Masplot.a

# IOCs

***Hashes do Arquivo***

MD5 66ff06fe9a8b9b4d0eaaf5bd96bf8f1f

SHA1 e697dfafeb2855e450eeacb8ea3e57e38306fc9c

SHA256 9fa3fbd02991bb1eb2ed96f727e11ed25d4e6471a5d474925662eae10aa7c066

Vhash 9574a7b0557beab48d85c57760abf785

SSDEEP 393216:D+3v2qNGEs17Dfcx7SNeeuoSce+EL6gjp4PPGeRrM1iMrYjaDg8JN:DEB+7Dfciee5XM6gV4HDRr+nrYjaDnN

***Hashes Certificado de Assinante***

v1 signature: True

v2 signature: False

v3 signature: False

Found 1 unique certificates

Subject: ST=Portugal

Signature Algorithm: rsassa_pkcs1v15

Valid From: 2009-09-22 14:53:51+00:00

Valid To: 2034-09-16 14:53:51+00:00

Issuer: ST=Portugal

Serial Number: 0x4b7e2629

Hash Algorithm: sha256

md5: bb8020d9103cec9b9ba7fd63ec4f12d2

sha1: 197583c8271eb67c1874059c11bb146521bc3fbe

sha256: aee62177c34deef2d9b5afa6ab04e9ec12a368ff38919b8976be5b86c77ebcbe

sha512: a14da614d3943ebd3e2d605b4cd040d76408f5ab52ea5c984743d6bbe2aa7788fa5addb4147b4fbb74493a49e646aaad1ad6f7cae368b9b9e965c0eed0fd7fba

***C2 Address***

23.61.119.125 
104.18.203.75 
52.0.242.118 
3.228.148.212 
104.71.11.240 
13.232.53.153 
34.246.211.67 
52.50.195.154 
104.71.11.240 
99.81.202.171 
63.32.228.40 
13.127.73.194 
52.23.47.7 
37.48.77.171 
52.51.4.81
69.28.165.134
200.136.36.94
104.20.108.41
221.122.73.6
104.45.180.93
200.123.197.136
52.150.55.162
54.85.91.123
104.92.79.28
104.18.203.75
200.152.165.205
216.58.202.206
104.18.41.37
76.76.21.21
140.82.114.4
52.8.149.90
205.185.216.42
205.185.216.10
52.188.35.179
37.48.77.180
37.48.77.162
172.217.30.75
13.35.111.94
64.225.57.187
172.217.172.206
172.67.18.172
23.38.153.7
23.61.119.125
104.18.203.75
35.171.210.186
52.154.69.245
52.150.55.162
34.243.15.205
52.186.42.194
104.244.42.193
23.61.119.125
104.71.11.240
37.48.77.165
37.48.77.162
34.242.190.212
13.227.106.126
18.234.79.235
54.154.230.214
93.184.216.34
157.240.222.35
20.42.24.39
192.48.236.11
83.173.251.158
216.58.202.174
74.50.62.60
23.38.153.7

