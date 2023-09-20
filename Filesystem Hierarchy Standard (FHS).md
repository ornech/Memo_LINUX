# MENO
## Filesystem Hierarchy Standard (FHS)
Le Filesystem Hierarchy Standard (FHS) est une norme qui définit l'organisation, les rôles et la structure des fichiers et répertoires dans un système de fichiers Linux. Elle fournit des directives et des recommandations pour assurer la cohérence et la portabilité entre les différentes distributions Linux. Voici un mémo sur le Filesystem Hierarchy Standard :

Dossier | Description
 --- | --- 
/ (root) | Le répertoire racine du système de fichiers. Tous les autres répertoires et fichiers sont organisés sous ce répertoire.
/bin  | Contient les exécutables essentiels du système accessibles à tous les utilisateurs.
/boot | Contient les fichiers nécessaires au démarrage du système, tels que les fichiers de configuration du chargeur d'amorçage (bootloader) et les noyaux du système.
/dev | Contient les fichiers de périphériques qui représentent les différents matériels et périphériques du système.
/etc | Contient les fichiers de configuration spécifiques au système et aux applications.
/home | Répertoire des utilisateurs, où chaque utilisateur a son propre répertoire personnel.
/lib | Bibliothèques partagées nécessaires au fonctionnement des exécutables du système
/media | Point de montage pour les supports amovibles tels que les CD-ROM, les clés USB, etc.
/mnt | Point de montage temporaire pour les systèmes de fichiers supplémentaires.
/opt | Contient les logiciels et packages optionnels installés sur le système.
/proc | Pseudo-système de fichiers qui joue le rôle d’interface avec le noyau pour accéder aux informations du noyau et des processus en cours d'exécution.
/root | Le répertoire personnel de l'utilisateur root (administrateur système).
/sbin | Contient les exécutables système essentiels destinés à l'administration et à la maintenance du système.
/tmp | Répertoire temporaire pour les fichiers temporaires créés par les applications et les utilisateurs.
/usr | Contient les fichiers, les bibliothèques et les ressources partagées utilisées par les applications installées.
/var | Contient les données variables du système, telles que les fichiers journaux (logs), les spools d'impression et les bases de données.

Notez que certaines distributions Linux peuvent varier par rapport à cette norme pour répondre à leurs besoins spécifiques, mais la plupart des distributions respectent les principes fondamentaux de cette norme.
