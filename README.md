# Creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:
### Step 1:
Install kali linux either in partition or virtual box or in live mode.

### Step 2:
Investigate on the various categories of tools as follows.

### Step 3:
Open terminal and try execute some kali linux commands.

### DEVELOPED BY : Gumma Dileep Kumar
### REGISTER NO : 212222240032

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. The command sudo setoolkit in the prompt gives menu with set prompt:
![ethical_7 1](https://github.com/gummadileepkumar/creating-a-backdoor-with-SET/assets/118707761/3129315f-215e-4c86-8409-ebaa1c1d9700)


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:


![ethical_7 2](https://github.com/gummadileepkumar/creating-a-backdoor-with-SET/assets/118707761/50182e45-d434-4e4c-b549-0eaae52ec198)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:


![ethical_7 3](https://github.com/gummadileepkumar/creating-a-backdoor-with-SET/assets/118707761/7236540f-574c-4161-841b-3f830326dbf9)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected: 

![ethical_7 4](https://github.com/gummadileepkumar/creating-a-backdoor-with-SET/assets/118707761/938bead6-3c45-4fcd-a05e-f80eab8ecf3e)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![ethical_7 5](https://github.com/gummadileepkumar/creating-a-backdoor-with-SET/assets/118707761/4a1d1605-62dd-40c5-9c9a-98b79512bc25)


It shows the following screen in which the option Google can be selected: 

![ethical_7 6](https://github.com/gummadileepkumar/creating-a-backdoor-with-SET/assets/118707761/62731765-85a0-42dc-9bf0-fd553aacf030)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done: 

![ethical_7 7](https://github.com/gummadileepkumar/creating-a-backdoor-with-SET/assets/118707761/02175088-76e3-45b7-9c8f-bd96c6a6d9bc)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password 

![ethical_7 8](https://github.com/gummadileepkumar/creating-a-backdoor-with-SET/assets/118707761/c842f11b-1541-451b-a2e9-cf1f7238a2f2)


SET logs the information regarding the Google credentials: 

![ethical_7 9](https://github.com/gummadileepkumar/creating-a-backdoor-with-SET/assets/118707761/fcaa20eb-3386-4845-8851-84c2c79f328e)


SET logs the information in the xml file under /root/.set directory:

![ethical_7 10](https://github.com/gummadileepkumar/creating-a-backdoor-with-SET/assets/118707761/134cf982-7542-4013-8eec-ab3800a297fb)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
