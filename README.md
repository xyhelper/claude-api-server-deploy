# claude-API-Server-Deploy

Claude API Server 快速部署脚本库




## 前置条件
- 本项目为商业服务,依赖于`xyhelper.cn`提供的接入点服务运行
- 一台至少 2 核 2G 内存的服务器,推荐使用香港、新加坡、日本地区的服务器,可以兼顾国内访问。
- 安装了 docker 和 docker-compose
- 安装了 git



## 自动部署

在服务器上执行以下命令即可

```bash
curl -sSfL https://raw.githubusercontent.com/xyhelper/claude-api-server-deploy/master/quick-install.sh | bash

```

## 手动部署

1. 克隆本仓库到服务器上

```bash
git clone --depth=1 https://github.com/xyhelper/claude-api-server-deploy.git claude-api-server
```

2. 进入目录

```bash
cd claude-api-server
```

3. 启动服务

```bash
./deploy.sh
```

## 使用方法

用户端访问地址为 http://服务器 ip:8001

管理后台地址为 http://服务器 ip:9000/xyhelper/

默认用户名密码为 admin/123456

## 模拟API接口地址

http://服务器IP:8001/v1/chat/completions

