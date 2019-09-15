# Docker版本僵尸毁灭工程
本项目为方便玩家在非Windows系统中玩《僵尸毁灭工程》而制作。

## 安装说明

前提: 已安装docker，并准备好《僵尸毁灭工程》安装exe文件

### 1、安装Yarn依赖管理工具

brew install yarn

### 2、放入僵尸毁灭工程安装文件

将Project_Zomboid_v40.43_setup.exe放入install文件夹下

### 3、创建docker镜像

yarn build

### 4、创建docker容器

yarn create

> 创建好容器后，会自动运行容器

### 5、浏览器中打开“http://127.0.0.1:6080/#/”

用户名: root
密码: 123

### 6、安装《僵尸毁灭工程》
wine /install/Project_Zomboid_v40.43_setup.exe
之后手动安装

### 7.运行游戏
然后就可以正常游戏了

## 项目docker容器使用说明

### 运行

yarn start

### 停止

yarn stop

### 暂停

yarn pause

### 恢复

yarn unpause

### 删除

yarn remove

### 创建

yarn create
