# Git

## 一、常见命令

- git init : 初始化git仓库，即将一个文件夹初始化为一个git仓库。具体操作是创建一个.git隐藏文件夹
- git status ： 查看文件的状态
- git add  (（. or 文件名）后面跟一点代表将所有新添加的或者新修改的文件放入缓存区，也可指直接跟文件名)
- git commit -m  "注释" 将缓存区的文件提交到仓库缓存区，并且附带注释信息。
- git log ：查看所有产生的commit记录
- git config -l ：查看自己的配置，默认配置都在.git/config文件中
- git  push -u origin   master（远程仓库名）: 将某个文件从缓存区退送到远程仓库。
- git push origin   test ：test （从本地test分支提交到远程test分支，如果远程没有test分支，会自动创建）

```
注：在这个过程中，首先得进入git的本地目录 然后在目录中创建文件或者文件夹 。创建好了之后利用git add 将其推送至本地缓存区，然后git commit将其提交到远程缓存区，之后 git push 将其提交到仓库
```

## 二、分支操作

-  git branch : 查看当前所在分支和分支个数等
- git  checkout  分支名  ：切换分支
- git  branch -d 分支名 ：删除分支
- git branch  分支名 ： 新建分支
- git checkout -b 分支名 ：创建分支并进入该分支
- git merge ： 合并分支
- git fetch -a :获取所有分支
- git merge origin  分支名 ： 合并到本地分支

## 三、克隆仓库等相关操作

- git clone url(仓库地址)    克隆远程仓库  （会克隆仓库的本地文件的所有分支和文件）



 