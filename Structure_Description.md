# 项目结构说明

## Docker环境配置
- 使用Ubuntu 22.04作为基础镜像
- 容器名称：github-collab-new
- 端口映射：
  - SSH: 2223 -> 22
  - Web应用: 3001 -> 3000
- 已安装软件包：
  - openssh-server
  - git
  - nano
  - sudo
  - python3
  - python3-pip
  - python3-venv
  - nodejs

## Python环境
- 基础包：
  - flask
  - flask-cors
  - flask-sock
  - whisper
  - torch
  - soundfile
  - numpy

## Node.js环境
- Node.js 18.x
- 全局包：
  - create-react-app

## 用户账户
- dev1 (U1)
  - 用户名：U1
  - 登录账户：dev1
  - 密码：2136
  - 权限：sudo

- dev2 (U2)
  - 用户名：U2
  - 登录账户：dev2
  - 密码：2136
  - 权限：sudo

- dev3 (U3)
  - 用户名：U3
  - 登录账户：dev3
  - 密码：2136
  - 权限：sudo

- dev4 (U4)
  - 用户名：U4
  - 登录账户：dev4
  - 密码：2136
  - 权限：sudo

## 目录结构
/.git - Git版本控制目录
/.cursor - Cursor IDE配置目录
/Structure_Description.md - 本文件，描述项目结构
/log.md - 项目修改日志
/home/dev[1-4] - 用户主目录 