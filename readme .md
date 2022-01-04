上課心得:

小賴老師著重於原理,之前老師的教法,感覺比較像複製code,但很多邏輯方面還是有些模糊,老師分享了許多業界上的問題和團隊問題,並且如何解決,十分受用,目前教得最仔細的老師!

1.複習 git,git hub 的用法 還有教一些之前沒用過的指令

$ git config --list

cat 印出檔案內容
cat ~/.gitconfig

[alias] co = checkout br = branch ci = commit st = status lg = log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cd) %C(bold blue)<%an>%Creset' --abbrev-commit --date=iso l = log --oneline --graph la = log --all --oneline --decorate --graph

查看 git 的狀態
$ git status $ git st

把檔案加入
$ git add test.txt

提交這次的修改
$ git commit -m "正確填寫這次 commit 的資訊" $ git ci -m "正確填寫這次 commit 的資訊"

檢視這次修改的差異
$ git diff

已經加入過的檔案，又有修改的話，一樣要再 add 一次，才可以 commit
$ git add test.txt $ git ci -m "xxxx"

針對已經加入過的檔案，可以直接用以下指令提交
$ git ci -am "xxxxx"

可以「反悔」加入暫存區
$ git restore --staged test.txt

反悔剛剛的修改
$ git restore test.txt

查看提交紀錄
$ git log

查看特定檔案的紀錄
$ git log <檔名>

查看檔案修改細節
$ git log -p test.txt

可以針對 commit 訊息做搜尋
$ git log --grep="delete"

查看內容是誰編寫的
$ git blame test.txt

3.Scrum 工作術 https://medium.com/doflowy/%E4%BB%80%E9%BA%BC%E6%98%AFscrum-%E4%B8%8D%E6%98%AF%E5%B7%A5%E7%A8%8B%E5%B8%AB%E4%B9%9F%E8%83%BD%E6%87%82%E7%9A%84scrum%E5%85%A5%E9%96%80%E6%95%99%E5%AD%B8-1cc6683575f8

4.markdown 語法: https://markdown.tw/

5.git flow code review 的規範 https://google.github.io/eng-practices/review/reviewer/

學習 ES6 的語法 https://gretema.github.io/javascript/20200504/221423942/

