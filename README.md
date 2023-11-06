# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:
Install kali linux either in partition or virtual box or in live mode

### Step 2:
Investigate on the various categories of tools as follows:

### Step 3:
Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
![image](https://github.com/sakthipriyadhanusu/creating-a-backdoor-with-SET/assets/119393194/e93ed3fd-84a5-4211-b74f-351406999a2b)

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/sakthipriyadhanusu/creating-a-backdoor-with-SET/assets/119393194/aa33f15e-8848-492d-9427-da921c35acfd)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/sakthipriyadhanusu/creating-a-backdoor-with-SET/assets/119393194/260d5a74-2e3d-47a9-9d9c-e2259b9ebb0b)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/sakthipriyadhanusu/creating-a-backdoor-with-SET/assets/119393194/749921a4-7945-4ae8-8356-ba87946feac1)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/sakthipriyadhanusu/creating-a-backdoor-with-SET/assets/119393194/b7269853-7894-42f8-be07-ea6e59fd8a9e)

It shows the following screen in which the option Google can be selected:

![image](https://github.com/sakthipriyadhanusu/creating-a-backdoor-with-SET/assets/119393194/7d883ece-4ac9-4cca-b68c-36dc93b7d860)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/sakthipriyadhanusu/creating-a-backdoor-with-SET/assets/119393194/2408e527-1859-4ae9-b696-fab88919fc82)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/sakthipriyadhanusu/creating-a-backdoor-with-SET/assets/119393194/675cc5fc-a17c-480e-b7b0-fb540ce9440e)

SET logs the information regarding the Google credentials:

![image](https://github.com/sakthipriyadhanusu/creating-a-backdoor-with-SET/assets/119393194/18ec3abd-e067-493d-b378-a24dcbca77b4)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/sakthipriyadhanusu/creating-a-backdoor-with-SET/assets/119393194/2e2a29c8-cc69-4ef3-8112-35965a28744f)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
