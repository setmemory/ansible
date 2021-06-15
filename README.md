
#### 从github官网克隆代码到本机
`git clone https://github.com/tmpyun/ansible.git`
<br></br>

#### 配置git自定用户名
`git config --global user.name "自定义名称"`
<br></br>

#### 配置git用户邮箱账号，github官网申请的用户名或邮箱账号
`git config --global user.email "github账号"`
<br></br>

#### 查看git客户端配置信息
`git config --list`
<br></br>

#### 把本机工作区代码文件到本机git暂存区
`git add * `
<br></br>

#### 把本机git暂存区提交到本机git分支
`git commit -m "modify"`
<br></br>

#### 把本机git分支推送到远程git仓库的master（分支名称）分支
`git push -u origin master`
<br></br>

#### 修改远程git仓库的地址
`git remote add origin https://github.com/tmpyun/java.git`
<br></br>

### 查看与撤消工作区到缓存区之前（git add命令之前的操作）
1. `git diff`
2. `git checkout . `

<br></br>

### 查看与撤消暂存区到本地git仓储前（git commit命令之前和git add之后的操作）
`git diff`
`git checkout .`
<br></br>


<br></br>
<br></br>

#### github官网刚创建的一个项目需要执行如下git操作:
+ echo "# ansible" >> README.md
+ git init
+ git add README.md
+ git commit -m "first commit"
+ git branch -M master
+ git remote add origin https://github.com/tmpyun/ansible.git
+ git push -u origin master

