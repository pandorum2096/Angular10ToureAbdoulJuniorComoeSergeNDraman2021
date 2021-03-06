# Angular10ToureAbdoulJuniorComoeSergeNDraman2021
******************************************************************************************************
PROJET ANGULAR 10: ASSIGNMENTS


Binôme étudiants MBDS2 Cote d'Ivoire: 

- TOURE ABDOUL JUNIOR
- N'DRAMAN COMOE SERGE

*******************************************************************************************************
Notre projet etant deja hebergé sur heroku:

site du API: https://api2096.herokuapp.com/api/assignments 

site du projet : https://mbdsassignments.herokuapp.com/

Login : admin ou login
Password : admin ou password

*******************************************************************************************************

I-COMMENT FAIRE FONCTIONNER LE PROJET

Le projet étant telechargé a partir de la plateforme Github, vous devez taper ces commandes ci-dessous:

a) Ouvrir le projet API

-npm install      =======> pour mettre a jour les modules node js de API en local ============> mais le projet etant sur heroku pas besoin
-node server.js   =======> pour lancer le serveur API en local ============> mais le projet etant sur heroku pas besoin

b) Ouvrir le projet toureetserge_angular10

-npm install      =======> pour mettre a jour les modules node js du projet en local ============> mais le projet etant sur heroku pas besoin
-ng serve   =======> pour lancer le serveur du projet en local ============> mais le projet etant sur heroku pas besoin

c) Dossier images contenant des images des differents professeurs pour les insertions en local si possible


************************************ CONTRIBUTIONS APPORTEES AU PROJET *******************************

II- DETAIL DU TRAVAIL EFFECTUE à 100%:


•	une gestion de login/password
          o	Cas simple : vous codez en dur dans le service d'authentification une liste de login/passwords valides.
          Login : admin ou login
          Password : admin ou password
          
•	Nous avons ajouté une session qui empeche la page de perdre la session en cours lors de l'actualisation de la page:
        


•	Ajouter de nouvelles propriétés au modèle des Assignments:
          o	Nom (nom de l'élève)
          o	Prenom (prenom de l'élève)
          o	Matière (Base de données, Technologies Web, Grails, etc.)
          o	Une image unique est associée à chaque matière et une photo differente pour chaque prof
          o	Note sur 20, on ne peut marquer "rendu" un Assignment qui n'a pas été noté.
          o	Remarques


•	Améliorer l'affichage des Assignments:
          o	il faudra mettre à jour les différents endroits où les Assignments sont affichés/édités/saisis, en particulier :
            - chaque Assignment sous forme d'une Material Card
            - le titre, la date, l'élève, une petite image illustrant la matière, la photo du prof en petit en haut à droite.
          o	La vue détails montrera en plus les remarques, la note s'il a été rendu, etc.
          o	Les formulaires d'ajout  proposent un choix fixe de matières et un choix de photo de professeur, les photos sont stockées sur le serveur.


•	Afficher les Assignments dans deux onglets séparés selon qu'ils ont été rendus ou pas encore rendus
          o	Lorsqu'on met une note à un Assignment , on a possibilité de choisir le rendu a false ou a true et apparaitra dans l'onglet "Rendu"

• hébergement sur Heroku.com

•	Possibilité d'ajouter une photo sur le serveur API
          o	Lorsqu'on met une note à un Assignment , on a possibilité de choisir le rendu a false ou a true et apparaitra dans l'onglet "Rendu"

************************************************************************************************************

III- FONCTIONNEMENT DE LA PLATEFORME


1) Une foie sur la plateforme, l'utilisateur (le professeur) se connecte en mettant son login et son passsword.

2) Ainsi, il pourra effectuer certaines actions comme:
 - il peut voir la liste des assignments en cliquant sur le buouton 'lister assignments'
 - il peut créer des assignments en remplissant le formulaire 
 - S'il n'est pas connecté, il ne peut effectuer aucune action
 - Le professeur peut voir les informations concernant l'assignment qui a été crée et peut effecctuer des 
   modifications la dessus et supprimer l'assignment.
 - Apres avoir fini ses operations, il peut se deconnecter et sera réedigé vers la page de connexion automatiquement.  
