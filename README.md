# H1 GitHub Zadatak 2.
## H2 Pull, Push, Approve PR

### H3 Zadatak Sara:
1. Kreirati repository na Githubu ‘QAteam’
2. Neka bude public
3. Otici na Command line i odrediti lokaciju gde ce repo da bude smesten (e.g Desktop, Documents)
4. Klonirati repo : ```git clone git@github.com:saravukobrat/QAteam.git```
5. Uci u kloniran repo i proveriti sa ```ls -a``` sta sve ima u njemu
6. Napraviti i komitovati README.md file sa porukom “First commit”
7. ```git push```
8. Otici na Github/QAteam/settings/Manage access i dodati vesnaatwork kao collaborator



### H3 Zadatak Bosko:
1. Visit [https://github.com/saravukobrat/QAteam]
2. Otici na Command line i odrediti na kom mestu ces klonirati repo sa githuba
3. Klonirati remote direktorijum na jedan od dva nacina:

a) ```git init```

	```git remote add origin git@github.com:saravukobrat/QAteam.git```
	
	```git pull origin master```

b) ```git clone git@github.com:saravukobrat/QAteam.git```

(Uvek mozemo proveriti sa ```git remote -v``` da li smo odredili origin)

4. Napraviti file DocQA.txt (```touch```)
5. Napraviti novu granu featureB sa ```git checkout -b featureB```
6. U file DocQA.txt uneti text ‘’Bosko”
7. Komitovati sa porukom ‘Bosko commit’
8. ```git push --set-upstream origin featureB```
9. Na github cemo videti new pull request
10. Kada kliknemo na Compare&pull request, sa desne strane cemo videti Assignees
11. Dodati Vesnu
12. Kliknuti Create pull request
13. Squash and merge, pa Confirm squash and merge
14. Moze a i ne mora da se obrise grana featureB


### H3 Zadatak Tamara:
1. Visit[ https://github.com/saravukobrat/QAteam]
2. Otici na Command line i odrediti na kom mestu ces klonirati repo sa githuba
3. Klonirati remote direktorijum na jedan od dva nacina:

a)	```git init```

	```git remote add origin git@github.com:saravukobrat/QAteam.git```
	
	```git pull origin master```

b)	```git clone git@github.com:saravukobrat/QAteam.git```	

(Uvek mozemo proveriti sa ```git remote -v``` da li smo odredili origin)

4. Napraviti novu granu featureT sa ```git checkout -b featureT```
5. U fajl DocQA text dodati text “Tamara”
6. Komitovati  sa porukom “Tamara commit”
7. ```git push``` (izaci ce na komandnoj linija komanda koju pokrenes: ```git push --set-upstream origin featureT```)
8. Na github cemo videti new pull request
9. Kada kliknemo na Compare&pull request, sa desne strane cemo videti Assignees
10. Dodati Vesnu 
11. Kliknuti Create pull request
12. Squash and merge, pa Confirm squash and merge
13. Moze a i ne mora da se obrise grana featureT

### H3 Zadatak Tijana:
1. Visit [https://github.com/saravukobrat/QAteam]
2. Otici na Command line i odrediti na kom mestu ces klonirati repo sa githuba
3. Klonirati remote direktorijum na jedan od dva nacina:

a)	```git init```

	```git remote add origin git@github.com:saravukobrat/QAteam.git```
	
	```git pull origin master```

b)	```git clone git@github.com:saravukobrat/QAteam.git```	

(Uvek mozemo proveriti sa ```git remote -v``` da li smo odredili origin)

4. Napraviti novu granu featureTij sa ```git checkout -b featureTij```
5. Proveriti sta sve ima u fajlu DocQA.txt sa ```cat DocQA.txt```
6. U fajl DocQA text dodati text “Tijana”
7. Komitovati  sa porukom “Tijana commit”
8. ```git push``` (izaci ce na komandnoj linija komanda koju pokrenes: ```git push --set-upstream origin featureTij```)
9. Na github cemo videti new pull request
10. Kada kliknemo na Compare&pull request, sa desne strane cemo videti Assignees
11. Dodati Vesnu 
12. Kliknuti Create pull request
13. Squash and merge, pa Confirm squash and merge
14. Moze a i ne mora da se obrise grana featureTij


### H3 Zadatak Relja:
1. Visit [https://github.com/saravukobrat/QAteam]
2. Otici na Command line i odrediti na kom mestu ces klonirati repo sa githuba
3. Klonirati remote direktorijum na jedan od dva nacina:

a)	```git init```

	```git remote add origin git@github.com:saravukobrat/QAteam.git```
	
	```git pull origin master```

b)	```git clone git@github.com:saravukobrat/QAteam.git```	

(Uvek mozemo proveriti sa ```git remote -v``` da li smo odredili origin)

4. Napraviti novu granu featureR sa ```git checkout -b featureR```
5. Proveriti sta sve ima u fajlu DocQA.txt sa ```cat DocQA.txt```
6. U fajl DocQA text dodati text “Relja”
7. Komitovati  sa porukom “Relja commit”
8. ```git push``` (izaci ce na komandnoj linija komanda koju pokrenes: ```git push --set-upstream origin featureR```)
9. Na github cemo videti new pull request
10. Kada kliknemo na Compare&pull request, sa desne strane cemo videti Assignees
11. Dodati Vesnu 
12. Kliknuti Create pull request
12. Squash and merge, pa Confirm squash and merge
13. Moze a i ne mora da se obrise grana featureR

### H3 Rezultat:
Kada odemo na command liniju

i odradimo ```git clone git@github.com:saravukobrat/first.git```

```cat DocQA.txt```

videcemo sledece:

Bosko

Tamara

Tijana

Relja


