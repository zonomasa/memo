memo
====
$ mkdir test
$ cd test
$ touch hoge.c
$ git init
$ git add .
$ git commit -m "first commit" #ローカル
$ git remote add origin git@github.com:ユーザ名/レポジトリ名.git
$ git fetch && git merge origin/master 
$ git push -u origin master
