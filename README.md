# node建站攻略(二期)——网站升级
- [imooc视频地址](http://www.imooc.com/learn/197)
- 本人根据视频敲的源代码，仅供参考

## 项目架构
- 基于MEAN架构(Mongo,Express,Angular,Node)

## 准备工作
- 安装node&mongodb

## 安装教程
- clone 源码
- 执行npm install
- 启动mongodb,OS-X系统，进入mongdb/bin下执行`./mongod`开启数据库
- 启动grunt运行

## 查看数据库
- 进入mongodb/bin目录下执行`./mongo`打开数据库，执行`use [数据库名]`查看数据库

## 一些mongodb查询语法
- 更新用户信息字段：db.users.update({"_id":ObjectId("5462e471a89b09af16c5d3aa")},{$set:{role:0,workId:78744,jobDesc:'前端开发工程师'}})
