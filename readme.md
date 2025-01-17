Cours Github 2025

= Première étape : initialiser un repo sur Github

- créer dans le Github un nouveau repository
- Nommer le repository comme vous le souhaitez (ajoutez une description si vous le souhaitez)
- Vous pouvez choisir sa visibilité : Public ou privé
- Allez en bas de la page sur le bouton "Create repository"

Votre repository est maintenant créé, vous allez pouvoir faire votre premier commit.

= Faire son premier commit.

Vous allez vous rendre compte qu'il y'a un petit encadré nommé "Quick setup" qui propose deux possibilité : 

SSH ou HTTPS

Initialisation du Github sur votre machine

Sur Visual Studio Code :

    - Ouvrir un terminal (4 possibilités différentes, vous choisissez)
            Menu terminal : Nouveau terminal
            Menu affichage = terminal
            CTRL + ù
            En bas à gauche, vous avez une icône triangle et rond, cloqiez dessus.

Vous pouvez maintenant initialiser Git sur votre machine sur le terminal qui est ouvert avec la commande "git.init"

Une fois initialisé, vous allez devoir indiquer quel(s) fichier(s) vous souhaitez envoyer sur Github. Pour cela :
            git


            Markdown

            Pour la mise en forme; utilisez le language Markdown : https://www.markdownguide.org/basic-syntax/

            Evitez d'envoyer des fichiers/dossiers sur Github

            Vous avez la possibilité de dire à Github qu'il y'a certains fichiers et dossiers que vous ne souhaitez
            pas partager sur votre repository.
            Créer un dossier ".gitignore" à la racine de votre dossier/projet.

            Dans le fichier ".gitignore" vous devez ajouter ligne par ligne les fichiers dossiers que vous ne voulez pas
            ajouter au repository.

            exemple : (on met point pour module sinon considéré comme un dossier)


            .code.js 
            node_modules ()
            .css
            .img

            convention 

            quand c'est un dossier on l'écrit tel quel
            quand c'est un fichier on l'écrit avec un .avant le nom



            Exercie

            - Dans un de vos repository, ajoutez un nouveau fichier (.js, .html, .autre on s'en fiche)
            - Une fois le fichier ajouté, publier la modification sur github (votre repo doit avoir le fichier)
            - Débrouillez-vous ensuite pour supprimer le fichier que vous venez d'ajouter et répercuter la suppression
            sur votre repo github

            Exercice 2

            - créez une dossier dans votre repo github
            -ajoutez un fichier dans ce dossierajoutez un fichier dans .gitignore dans votre projet
            - publiez la modification sur Github
            - Vous ne devez pas avoir le nouveau dssier dans votre repo Github