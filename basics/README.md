0. Where am I?

Affiche tout le chemin d'accés depuis la ou on est

1. Whats in ther  
 
Affiche tout les fichiers et dossiers a l'endroit ou l'on ce trouve
 
2. There is no place like home
 
permet de ce dé placer dans les dossiers
 
3. The long format
 
Afficher le contenu du répertoire actuel dans un format long
 
4. Hidden files
 
Afficher le contenu du répertoire actuel, y compris les fichiers cachés
 
5. I love numbers
 
Afficher le contenu du répertoire actuel.

6. Welcome

Ce script crée un répertoire nommé my_first_directory dans le répertoire /tmp/

7. Betty in my first directory

mv /tmp/betty /tmp/my_first_directory permet de déplacer le fichier Betty de /tmp/ vers /tmp/my_first_directory

8. Bye bye Betty

rm /tmp/my_first_directory/betty permet de suprimer le fichier betty

9. Bye bye My first directory

rmdir /tmp/my_first_directory permet de suprimer le dossier my_first_directory

10. Back to the future

cd - permet de remplacer le répertoire de travail par le précédent.

11. Lists

ls -la . .. /boot permet de répertorier tous les fichiers (même ceux dont les noms commencent par un point, qui sont normalement cachés) dans le répertoire courant et le parent du répertoire de travail et du répertoire /boot (dans cet ordre), au format long.

12. File type

file /tmp/iamafile permet d'imprimer le type du fichier nommé iamafile

13. We are symbols, and inhabit symbols

ln -s /bin/ls __ls__ permet créer un lien symbolique vers /bin/ls, nommé __ls__. Le lien symbolique doit être créé dans le répertoire de travail actuel.

14. Copy HTML files

cp -u /tmp/test_html/*.html /tmp/ ce script permet de copier tous les fichiers HTML du répertoire de travail actuel vers le parent du répertoire de travail, mais ne copie que les fichiers qui n’existaient pas dans le parent du répertoire de travail ou qui étaient plus récents que les versions du parent du répertoire de travail.

15. Let’s move

mv [[:upper:]]* /tmp/u ce script permet de déplacer tout les fichier commencant par une lettre majuscule vers le répertoire /tmp/u

16. Clean Emacs

rm /tmp/test_emacs/*~ ce script permet de surpprimer tout les fichier du répertoire de travail actuel qui ce termine par le caractère ~

17. Tree

mkdir -p /tmp/test_tree/welcome/to/school ce script permet de crée les répertoire welcome/ , welcome/to/ et welcome/to/school dans le répertoire courrant 
