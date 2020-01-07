# poi200107submodules
submodules

```
//git clone --recurse-submodules --shallow-submodules https://github.com/wotupset/poi200107.git 
git clone --depth 1 https://github.com/wotupset/poi200107submodules.git poi200107submodules

git clone --depth 1 https://github.com/wotupset/poi200107.git poi200107-b
git clone https://github.com/wotupset/poi200107.git poi200107-b

git clone --single-branch --branch poi --depth 1 https://github.com/wotupset/poi200107.git poi200107-b


git submodule init
git submodule update
git submodule sync


git checkout master
git pull master
git push master
git pull origin master && git push origin master
git add . && git commit -a -m "2020.01.07" && git push origin master



git submodule add https://github.com/wotupset/poi200107.git 
git submodule add -b new1 https://github.com/wotupset/poi200107submodules.git 05


git status
git submodule status


git submodule update --remote --merge

git branch
git branch -a

git rm --cached 01
git rm 01



https://blog.wu-boy.com/2011/09/introduction-to-git-submodule/
https://blog.longwin.com.tw/2015/05/git-submodule-add-remove-2015/
git submodule update --recursive --remote --merge --force
git pull --recurse-submodules
https://blog.csdn.net/lyy_whg/article/details/9363157


usage: git submodule [--quiet] [--cached]
   or: git submodule [--quiet] add [-b <branch>] [-f|--force] [--name <name>] [--reference <repository>] [--] <repository> [<path>]
   or: git submodule [--quiet] status [--cached] [--recursive] [--] [<path>...]
   or: git submodule [--quiet] init [--] [<path>...]
   or: git submodule [--quiet] deinit [-f|--force] (--all| [--] <path>...)
   or: git submodule [--quiet] update [--init] [--remote] [-N|--no-fetch] [-f|--force] [--checkout|--merge|--rebase] [--[no-]recommend-shallow] [--reference <repository>] [--recursive] [--] [<path>...]
   or: git submodule [--quiet] set-branch (--default|--branch <branch>) [--] <path>
   or: git submodule [--quiet] summary [--cached|--files] [--summary-limit <n>] [commit] [--] [<path>...]
   or: git submodule [--quiet] foreach [--recursive] <command>
   or: git submodule [--quiet] sync [--recursive] [--] [<path>...]
   or: git submodule [--quiet] absorbgitdirs [--] [<path>...]
   
   
   
   
```
