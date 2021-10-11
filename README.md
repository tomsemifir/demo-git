## Creer un repository local : 
git init

## Suivre un fichier à enregistrer  :
git add *

## Enregistrer l'état des fichiers :
git commit -m "message"

## Pousser les modifications au repo distant : 
git push

## Voir l'état actuel des modifications : 
git status

## Récupère l'état actuel du repo distant :
git pull

## Connexion au repo distant : 
git remote add origin *origine* 
git remote remove origin

## Voir les derniers commits : 
git log

## Revenir à un commit précédent : 
git reset --hard *hash_du_commit* 

## Anuler le suivi d'un fichier : 
git rm --cached *nom_fichier*