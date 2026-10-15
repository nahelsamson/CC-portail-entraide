CC Portail d'entraide

1. Infos

Nom : Nahel Samson
Dépôt : https://github.com/nahelsamson/CC-portail-entraide
Commit de départ : '4a266e1'

2. Branches et modifications

'feature/accueil' : accueil libre sans inscription le jeudi à 16 h. Commit '4871474'
'feature/contact' : adresse e-mail rendue cliquable avec 'mailto:'. Commit '554c720'
'feature/tutorat' : ajout du tutorat individuel sur inscription à 16 h 30. Commit fourni 'a43f314'
'hotfix/duree' : correction de la durée des créneaux.

3. Fusions et conflit

Fusion accueil : '286323d'
Fusion contact : 'f86c7c1'
Fusion tutorat : 'e86b221'

Conflit dans 'index.html' : les branches accueil et tutorat modifiaient le même paragraphe.

Résolution : conservation des deux permanences et du lien e-mail. Suppression des marqueurs de conflit.

Vérification : 'git log --oneline --graph --decorate --all'. Le commit 'e86b221' a deux parents.

4. Correction de durée

Commit fautif : 'b88cc98' (200 minutes au lieu de 20).
Commit d'annulation : 'eeef6e3'.
Méthode : 'git revert', pour annuler le changement sans supprimer le commit d'origine.
Fusion de la correction dans 'main' par fast-forward.

5. Tests

Au chargement : 20 minutes par créneau.
Après deux ajouts : 2 créneaux, 40 minutes.
Après "Recommencer" : 0 créneau, 0 minute.
Lien e-mail : cliquable.

6. Publication

Dépôt public créé sur GitHub.
Branches publiées : 'main', 'feature/accueil', 'feature/contact', 'feature/tutorat', 'hotfix/duree'.
Dernier commit de 'main' : 'eeef6e3'.
README et permanences : README conservé avec le conseil de vérification du compteur. Les deux permanences sont présentes dans index.html : accueil libre sans inscription le jeudi à 16 h et tutorat individuel sur inscription le jeudi à 16 h 30. Le lien e-mail est également cliquable.

7. Utilisation de l'IA

Outil : ChatGPT.
Aide reçue : explications
