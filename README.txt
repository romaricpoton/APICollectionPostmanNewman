Installer 		  			 : T�l�charger nodeJs sur https://nodejs.org/fr/ puis installer 
Installer newman	  			 : nmp install newman
Installer newman reporter 			 : npm install -g newman-reporter-html
Installer newman reporterextra 			 : npm install -g newman-reporter-htmlextra



Enregidter la collection depuis POSTMAN : puis ===>
Ex�cution de test	  			  : newman run <Nom du fichier Json>
Ex�cution du test: html r�sultat sous format html : newman run <Nom du fichier Json> -r html
Ex�cution du test: html r�sultat sous format html : newman run <Nom du fichier Json> <option> -r htmlextra
                                                    (Ajouter l'option -n 3 pour trois it�ration)






C:\Users\romar\AppData\Roaming\npm\newman run D:\API_Collection\APIautomationPosts.json -r htmlextra


	
Propri�t�s globales
Variables d'environnement
PATH
C:\Program Files\nodejs
shell

C:\Windows\System32\cmd.exe