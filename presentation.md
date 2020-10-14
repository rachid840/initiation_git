2 formes differentes :
-github : plateforme collaborative, un des plus grands espace de stockage de travaux collaboratifs dans le monde, réseau social pour le travail, notament des developpeurs, on peut
créer des profil et deposer des projets,on peut les partage avec d'autres utilisateurs et suivre des comptes d 'autre personnes
-git : logiciel de controle de version, il gére la modificationsd 'un projet sans ecraser les partie ptrécèdentes

en vocabulaire, pour git, c est un programme ou l'on rentre les lignes de commmande git
les lignes de commande git ne peuvent etre utilisées que sur git

ce que l on appelle un dépots :c est un espace de stockage dédié a un projet, on peut le saugarder soit en ligne,soit dans un dossier
le controle de version de git est celui qu propose git 

le commit est la commande qui permet de prendre l'instantané qui stock en local nos identification

la branche est l' espace personnel sur celui qu'on travaille,on récuperela racine dans notre branche, une fois qu'on a réussi,on remet la branche dans le tronc commun

git init :initialise un nouveau dépots git (ou repository)

git config :permet de configurer , permet d'entrer ses identifiants github

git help :affiche les 21 commandes qui sont a disposition (on peut aussi utiliséesgit help init)

git status : indique sur lequelle branche on est et permet de savoir si les modifications ont été sauvegardés

git add : (utilisé avant le git commit) permet de faire un point sur ce qui a été ajouté de nouveau

git commit : c 'est la sauvegarde en local de nos modifications

git branch : utilisé pour créer une branche, pour travailler une partie du projet

git pull : permet d ' envoyer nos dernieres modifications en ligne

git push : récupere du travaille en ligne vers le local

git clone : dupliquer un répertoire ou projet depuis GitHubs

1- Presentation GitHub

1.1- de GitHub
Plateforme collaborative pour dev, plus grand espace de stockage de travaux collaborative dans le monde!
GitHub en lui-meme m'est plus rien de plus q'un reseau social comme fb.
Vous construisez un profil, vous y deposez des projets a partager et vous vous connectez avec d'autre utilisateurs
en suivant leurs comptes. Meme si la plupart des utilisateurs y deposent des projets de programmes ou de code,
rien ne vous empeche d'y placer des textes ou tout type de fichier a presenter dans vos repertoires de projets.

1.2- de Git
Git est un logiciel de controle de version, ce qui signifie qu'il gere les modifications d'un projet sans ecraser n'importe
quelle partie du projet.

2- Lexique de de Git et GitHub
    2.1 Vocabulaire
    **ligne de commande: le programme de l'ordinateur que nous utilisons pour entrer des commandes Git. Sur MacOS on parle de 
    Terminal et sur PC  c'est un programme non-natif que vous telecharger lorsque vous telecharger Git pour la premiere fois.

    **Depot: Un repertoire ou de l'espace de stockage ou vos projets peuvent vivre.
    Les utilisateurs de GitHub raccourcissent ca en "repo" pour "repository". Il peut etre un espace de stockage sur GitHub
    ou un autre hebergeur en ligne. A l'interieur d'un depot, vous pouvez conserver des fichiers de codes, des fichiers txt
    des images.

    **Controle de version: Fondamentalement, l'objectif pour lequel Git a ete concu. Quand vous avez un fichier Word, vous 
    l' ecrasez a chaque fois que vous sauvgrardez plusieur versions. Avec Git, vous n'est plus oblige de faire ca. Git conserve
    des "instantanes" de chaque point dans l'historique d'un projet, de sorte que vous ne pouvez jamais le perdre ou l'ecraser.

    **Commit: c'est la commande qui donne a git toute puissance.
    Quand vous committez, vous prenez un instantane, une photo de votre depot a ce stade vous donnant un point de controle
    que vous pouvez ensuite revaluer ou restaurer votre projet a un etat precedent.

    **Branche: Comment plusieurs personnes travaillant sur un projet en meme temps sans que Git ne s'embrouille?
    Habituellement, elle se debranchent du projet principal avec leur propres versions completes, des modifications qu'elles
    ont chacune produites de leur cote. Apres avoir termine, il est temps de fusionner cette branche pour la ramener vers
    la branche master, le repertoire principal du projet.

    2.2 Commandes specifiques Git 

    git init: inialise un nouveau depot git, vous permet executer les commandes Git qui suivent.

    git config: raccourci pour configurer, ceci est tout particulierement utile quand vous parametrez Git pour la premiere fois indentifiant et mot d'utilisateur.

    git help: oublie une commande? pour afficher les 21 commande de git.

    git status: verifie le statut de votre repo. Voir les fichiers et quelle sont les modifications a commiter et sur quelle branche
    ou repo vous etes en train de travailler.

    git add: ceci n'ajoute pas des fichiers dans votre repo, Au lieu de cela, cela porte de nouveaux fichiers a l'attestation de Git.
    Apres avoir ajoute des fichiers, ils dont inclus dans les instantanes du depot Git.

    git commit: la commande la plus importante de Git. Apres avoir effectue toute sorte de modification vous entrez ca afin de prendre
    un instantanes du depot. le mettre en memoire. On ecrit ca sous la forme de git commit -m 'votre message'. Le -m indique que 
    la section suivante de la commande devrait etre lu comme in message.

    git branche: Vous travaillez avec plusieurs collaborateurs et vous voulez produire des modification de votre cote? cette commande vous permet de construire une nouvelle branche, ou une chronologie des commits, des modifications et  des ajouts de fichiers qui sont completement les votres. Votre titre va apres la commande. Si vous vouliez creer une nouvelle branche appellee 'chats', vous saisiriez git branche chats.

    git checkout: c'est une commande de navigation qui vous permet de vous deplacer vers le repertoire que vous voulez verifier. Vous pouvez utiliser cette commande sous la forme de git checkout master pour regarder la branche master, ou git checkout chats pour regarder une autre branche.

    git merge: Lorsque vous avez fini de travailler sur une branche, vous pouvez fusionner vos modifications vers la branche master, qui est visible pour tous les collaborateur. git merge chats prendrait toutes les modifications que vous avez apportees a la branche chats et les ajoutera a la brache master.

    git push: si vous travaillez sur votre ordinateur en local et voud voulez que vos  commits soient visibles aussi en ligne sur Github, vous  pushez les modifications vers  GitHub avec cette commande.

    git  pull: si vous travaillez en local et que vous voulez la version la plus a jour de votre repo pour travailler dessus, vous pullez les modifications provenant de GitHub avec cette commande.

    git clone: permet de dupliquer, cloner un repo existant sur GitHub pour l'avoir en local. La commande git clone doit etre suivit de url de repo correspondant qui copie depuis GitHub direct.
