linux　如何使用git？
全局配置
git config --global user.name "tangm00"
git config --global user.email "tangmin007@foxmail.com"

在某个具体的目录下执行
1.git init : 将当前目录变成git可以管理的目录
2.git add readme.txt：将文件添加到暂存区中
3.git commit readme.txt "readme.txt提交":把文件提交到仓库，并添加提交信息
4.git status：查看状态，提交前后执行
5.git reflog:查看版本好
git reset --hard 版本号:恢复版本

