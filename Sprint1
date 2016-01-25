# BetaVersion 1.4.9
# Teran Valero A. Ray Enmanuel V021182424    
# https://github.com/rayvalero
# entrega primer split
// fuetes:

// http://www.maefloresta.com/portal/es/git.es

// http://rogerdudler.github.io/git-guide/index.es.html

// https://git-scm.com/book/es/v1/Fundamentos-de-Git-Trabajando-con-repositorios-remotos

// http://blog.solucionex.com/git/borrar-ultimo-commit-con-reset-y-revert-en-git

// http://aprendegit.com/como-deshacer-el-ultimo-commit-en-git/

// descarge e instale Git-2.7.0-32-bit.exe para windows 7

// https://git-scm.com/download/win

// de aqui en adelante todo se hizo por la consila de git bash

#Run

$ git config --global user.email rayvalero177

$ git config --global user.name RayValero

$ git init ray

$ cd ray

$ cd ..

#clonar repositorio

$ git clone https://github.com/ULAnux/mathematica

Cloning into 'mathematica'...
remote: Counting objects: 46, done.
remote: Compressing objects: 100% (41/41), done.
remote: Total 46 (delta 4), reused 46 (delta 4), pack-reused 0
Unpacking objects: 100% (46/46), done.
Checking connectivity... done.

$ git status

$ cd mathematica

#ver direccion

$ git remote

origin

#ver direccion espesifica

$ git remote -v

origin  https://github.com/ULAnux/mathematica (fetch)
origin  https://github.com/ULAnux/mathematica (push)

#clonar mi repositorio de prueba

$ git clone https://github.com/rayvalero/BetaVersion

Cloning into 'BetaVersion'...
remote: Counting objects: 14, done.
remote: Compressing objects: 100% (11/11), done.
remote: Total 14 (delta 1), reused 2 (delta 0), pack-reused 0
Unpacking objects: 100% (14/14), done.
Checking connectivity... done.

$ cd BetaVersion/

#añadir a index

$ git add README2.md

#incluimos al head 

$ git commit -m README2.md

#enviamos al repositorio

$ git push origin master

Counting objects: 2, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 270 bytes | 0 bytes/s, done.
Total 2 (delta 0), reused 0 (delta 0)
To https://github.com/rayvalero/BetaVersion
7ebcb51..ba658da  master -> master

#recuperar datos de tus repositorios remotos

$ git fetch origin

remote: Counting objects: 3, done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/rayvalero/BetaVersion
   ba658da..d684ae7  master     -> origin/master
   
#Descarga y guarda los cambios realizados desde un repositorio remoto

$ git pull

remote: Counting objects: 3, done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/rayvalero/BetaVersion
   d684ae7..d6e0c31  master     -> origin/master
Updating ba658da..d6e0c31
Fast-forward
 README.md | 33 +++++++++++++++++++++++++++++++--
 1 file changed, 31 insertions(+), 2 deletions(-)
 
#muestre mucha más información 

$ git remote show origin

* remote origin
  Fetch URL: https://github.com/rayvalero/BetaVersion
  Push  URL: https://github.com/rayvalero/BetaVersion
  HEAD branch: master
  Remote branch:
    master tracked
  Local branch configured for 'git pull':
    master merges with remote master
  Local ref configured for 'git push':
    master pushes to master (local out of date)

#Crea una nueva rama llamada "feature_x" y cámbiate a ella usando

$ git checkout -b feature_x

D       README1.md
Switched to a new branch 'feature_x'

#vuelve a la rama principal

$ git checkout master

D       README1.md
Switched to branch 'master'
Your branch is up-to-date with 'origin/master'.

#borra la rama

$ git branch -d feature_x

Deleted branch feature_x (was d6e0c31).

#Guarda los cambios desde la rama

$ git merge

Already up-to-date.

#reemplazar cambios locales usando el comando

$ git checkout -- README1.md

#indicando que retrocedemos a el comit HEAD~1 y perdemos todas las confirmaciones posteriores

$ git reset --hard HEAD~1

HEAD is now at ba658da README2.md

$ git reset --hard HEAD~1

HEAD is now at 88a628a README1.md

$ git reset --hard HEAD~1

HEAD is now at 9c76357 Update README.md

$ git reset --hard HEAD~1

HEAD is now at 8326ba6 Initial commit

#indicando que retrocedemos a el commit HEAD~1 y no perdemos los cambios de los commits posteriores

$ git reset --soft HEAD

#En caso de que queramos borrar un commit que ya hemos subido al servidor remoto

$ git revert HEAD

Vim: Error reading input, exiting...
Vim: Finished.
error: There was a problem with the editor 'vi'.
Please supply the message using either -m or -F option.

# Contribucion:

   *Mi contribucion personal a este proyecto en conjuntos "Un juego para aprender matemática y lógica", pienso que seria ampliar la base de datos de las preguntas y respuestas correctas del mismo, en la mayoria o preferiblemente en todos lo temas posibles que componen la materia y el juego*

