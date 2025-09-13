# vue-rabbit

## git使用

```shell
git init
初始化仓库,默认master

git add . 
当前文件放在暂存区

git commit -m "xxx" 
提交暂存区到本地git仓库

git log
查看提交

git remote add master https://github.com/xqs6666/vue-rabbit.git 
把「远程地址」起个别名叫 master，后面就不用再打长串 URL

git push -u master master:master 
第一个是远程仓库定义别名 第二个是本地仓库名字 第三个是你定义远程仓库叫啥
-u = --set-upstream，做完这次以后，直接 git push / git pull 即可。
```