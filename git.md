## GIT

#### 初始化仓库

```
git init
```
git add 命令来实现对指定文件的跟踪，然后执行 git commit 提交

#### 克隆现有的仓库
```
 git clone [url]
```
#### 检查当前文件状态
```
git status 
```
#### 查看已暂存和未暂存的修改
```
git diff
```
#### 提交更新
```
 git commit
```
#### 移除文件
```
git rm
```
#### 修改文件名
```
git mv file_from file_to
```
#### 分支创建
```
git branch 
```
#### 分支切换
```
it checkout 
```
#### 新建一个分支并同时切换到那个分支上

```
git checkout -b iss53
```
####  删除分支
 
1、删除本地分支
```
git branch -d [fileName]
```
1、删除远程分支
```
git push origin --delete [fileName]
```