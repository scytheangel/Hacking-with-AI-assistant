# Hacking-with-AI-assistant
Pentesting HackTHeBox using PentestGPT

<img width="1503" height="792" alt="image" src="https://github.com/user-attachments/assets/26b46f84-0dfa-438e-8568-2c63afb386d2" />

Copied the ip address and scanned with nmap

<img width="1232" height="520" alt="image" src="https://github.com/user-attachments/assets/61348a89-9b06-4327-9adc-deab5a7b8771" />

Did basic scan to see if host was online. Now I scan for any open ports

<img width="1240" height="387" alt="image" src="https://github.com/user-attachments/assets/25594d6b-9006-4a15-9705-3e200d24d352" />

Now we can ask an Ai for assistance, here I'm using PentestGPT but you can also use any other like WhiteRabbitNeo or whatever your comfortable with.

<img width="1478" height="947" alt="image" src="https://github.com/user-attachments/assets/4e8d9ebc-42f7-464a-b9b6-90dc742de965" />

<img width="1478" height="968" alt="image" src="https://github.com/user-attachments/assets/007d5716-9102-42af-97c7-98a31da0b298" />

<img width="1190" height="457" alt="image" src="https://github.com/user-attachments/assets/99dbd0c9-69ce-454b-9df9-de4eb2fbae7f" />

<h> Step 1:Deeper service enumeration </h>

<img width="1233" height="448" alt="image" src="https://github.com/user-attachments/assets/8f090294-4ca9-45ef-9ae5-231d843d4c85" />

<h> Step 2: Grab banners / fingerprint </h>

<img width="1238" height="269" alt="image" src="https://github.com/user-attachments/assets/13ae6bee-1987-4b9b-b523-d3037a036980" />

Consult with your Ai assistant for better understanding.

<img width="1479" height="1193" alt="image" src="https://github.com/user-attachments/assets/7d8531e6-b7d8-45ba-8cd7-57ea2753a262" />

<img width="1240" height="421" alt="image" src="https://github.com/user-attachments/assets/4b4ba601-d642-408c-9a2c-b3bfab073169" />

Consulting the Ai once more

<img width="1459" height="1152" alt="image" src="https://github.com/user-attachments/assets/122c7dc6-b17e-41d1-9fba-eb308e19cbfa" />

<img width="1239" height="946" alt="image" src="https://github.com/user-attachments/assets/0d4e0b99-ccb1-4411-8f67-15ab146d34a8" />

Run as root or install for your user

<img width="1466" height="1141" alt="image" src="https://github.com/user-attachments/assets/9d73ee0e-1109-4a1e-9774-2d6c05b727b4" />


<img width="1239" height="1061" alt="image" src="https://github.com/user-attachments/assets/0d505af8-886e-44d2-b073-126e3966e633" />

Ran into some issues. Here's what the Ai had to say.  "Found the actual problem: this version of SIPVicious installs its binaries under different names — sipvicious_svmap, not svmap. You already installed it successfully; you're just invoking the wrong name."

<img width="1245" height="1291" alt="image" src="https://github.com/user-attachments/assets/adcfcc53-2f59-40cd-8422-b9be80354861" />

Retry UDP with troubleshooting flags

<img width="1241" height="1186" alt="image" src="https://github.com/user-attachments/assets/10e4f359-bfb9-425c-bfd7-a7b5b9e3840e" />

