# belajarGIT
Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT


ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev
$ git init
Initialized empty Git repository in C:/Users/ASUS/OneDrive/Documents/webdev/.git/

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev (master)
$ git clone ^[[200~https://github.com/wndaangella/belajarGIT~
Cloning into 'belajarGIT~'...
fatal: protocol '?[200~https' is not supported

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev (master)
$ git clone https://github.com/wndaangella/belajarGIT
Cloning into 'belajarGIT'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev (master)
$ cd belajarGIT

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 1009 bytes | 84.00 KiB/s, done.
From https://github.com/wndaangella/belajarGIT
   c16fa5a..76a6457  main       -> origin/main
Updating c16fa5a..76a6457
Fast-forward
 README.md | 12 +++++++++++-
 1 file changed, 11 insertions(+), 1 deletion(-)

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git branch Tugas-git

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-git.txt

nothing added to commit but untracked files present (use "git add" to track)

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-git)
$ git status \
>
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-git.txt


ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-git)
$ git commit -m "tugas git"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'ASUS@Wanda-PC.(none)')

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-git)
$ git config --global user.email "wandapantouw@gmail.com"

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-git)
$ git config --global user.name "wndaangella"

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-git)
$ git commit -m "tugas git"
[Tugas-git cd2b2eb] tugas git
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git merge Tugas-git
Updating 76a6457..cd2b2eb
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 297 bytes | 297.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/wndaangella/belajarGIT
   76a6457..cd2b2eb  main -> main

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git branch Tugas-html

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
nothing to commit, working tree clean

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-html)
$ git add Tugas-html.txt
fatal: pathspec 'Tugas-html.txt' did not match any files

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-html)
$  git add Tugas-html.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-html.txt


ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-html)
$ git commit -m "Tugas Html"
[Tugas-html 834036b] Tugas Html
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git merge Tugas-html
Updating cd2b2eb..834036b
Fast-forward
 Tugas-html.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 313 bytes | 313.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/wndaangella/belajarGIT
   cd2b2eb..834036b  main -> main

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git branch Tugas-css

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-css)
$ git commit -m "tugasCss"
[Tugas-css 725e521] tugasCss
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git merge Tugas-css
Updating 834036b..725e521
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 350 bytes | 350.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/wndaangella/belajarGIT
   834036b..725e521  main -> main

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git branch Tugas-js

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-js)
$ git add Tugas-js
fatal: pathspec 'Tugas-js' did not match any files

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-js)
$ git commit -m "TugasJS"
[Tugas-js a61e547] TugasJS
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git merge Tugas-js
Updating 725e521..a61e547
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 268 bytes | 268.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/wndaangella/belajarGIT
   725e521..a61e547  main -> main

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git branch Tugas-midProject

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-midProject)
$ git add Tugas-js
fatal: pathspec 'Tugas-js' did not match any files

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject
fatal: pathspec 'Tugas-midProject' did not match any files

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject
fatal: pathspec 'Tugas-midProject' did not match any files

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-midProject)
$ git commit -m "Tugas-midProject"
[Tugas-midProject 4d8937c] Tugas-midProject
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git merge Tugas-midProject
Updating a61e547..4d8937c
Fast-forward
 Tugas-midProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 271 bytes | 271.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/wndaangella/belajarGIT
   a61e547..4d8937c  main -> main

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git branch Tugas-php

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-php)
$ git add Tugas-php
fatal: pathspec 'Tugas-php' did not match any files

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-php)
$ git commit -m "Tugas-php"
[Tugas-php 8b60832] Tugas-php
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git merge Tugas-php
Updating 4d8937c..8b60832
Fast-forward
 Tugas-php.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 244 bytes | 244.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/wndaangella/belajarGIT
   4d8937c..8b60832  main -> main

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git branch Tugas-finalProject

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject
fatal: pathspec 'Tugas-finalProject' did not match any files

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-finalProject)
$ git commit -m "Tugas-finalProject"
[Tugas-finalProject 872d477] Tugas-finalProject
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 8b60832..872d477
Fast-forward
 Tugas-finalProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

ASUS@Wanda-PC MINGW64 ~/OneDrive/Documents/webdev/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 243 bytes | 243.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/wndaangella/belajarGIT
   8b60832..872d477  main -> main

$ git push origin --all
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/wndaangella/belajarGIT
 * [new branch]      Tugas-css -> Tugas-css
 * [new branch]      Tugas-finalProject -> Tugas-finalProject
 * [new branch]      Tugas-git -> Tugas-git
 * [new branch]      Tugas-html -> Tugas-html
 * [new branch]      Tugas-js -> Tugas-js
 * [new branch]      Tugas-midProject -> Tugas-midProject
 * [new branch]      Tugas-php -> Tugas-php
