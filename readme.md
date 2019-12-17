# 分布式网络对战 RICHRUC 

本项目跨机器网络对战的人大版大富翁游戏。

# Preinstallation

JAVA环境

Eclipse Maven环境

# Launch

## 下载代码：

```git clone https://github.com/zhengyima/RICHRUCOnline.git```

## Server端部署：

1. 打开Eclipse，新建Maven项目。

2. 复制项目代码中的src目录至项目目录下，覆盖自动创建的src目录。

3. 在Eclipse刷新代码。

4. 运行RServerSocket类，即可开启服务端监听进程。

## Client 1（玩家一）：

1. 打开Eclipse，新建Maven项目。

2. 复制项目代码中的src目录至项目目录下，覆盖自动创建的src目录。

3. 在Eclipse刷新代码。

4. 更改ClientP类中的ip地址为Server的ip地址。

5. 运行MainMap类，生成Target目录。

6. 将源代码中的Target/classes/Public目录复制至项目的Target/classes目录下。

7. 重新运行MainMap类，开启游戏玩家1的游戏界面。

## Client 2（玩家二）：

重复Client的所有步骤，启动游戏玩家2的游戏界面。

