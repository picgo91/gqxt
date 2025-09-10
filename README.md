# 一、独立https

系统只支持centos7

## 一键下载命令：
```
yum install -y wget && wget https://raw.githubusercontent.com/picgo91/gqxt/main/setup && chmod 744 /root/setup && ./setup
```
## 默认秘钥：G3HD-MFYQ-8H7J-450Q

本文件介绍内容只用于学习交流，若有侵权，请联系删除！



# 二、Https过移动

## 一键下载命令：
```
iptables -I OUTPUT -p tcp --sport 443 -j NFQUEUE --queue-num 443 --queue-bypass
```
```
wget https://raw.githubusercontent.com/picgo91/gqxt/main/gyd && chmod 744 /root/gyd && ./gyd -q 443 -w 20 -c 10
```
## 默认秘钥：G3HD-MFYQ-8H7J-450Q

本文件介绍内容只用于学习交流，若有侵权，请联系删除！




# 三、真301
此应用程序是一个真正的 301 重定向应用程序，因为它在响应标头中响应 301 状态代码。

## 运行方式

http抢答301,系统ubutu22.04。

测试秘钥：G3HD-MFYQ-8H7J-450Q

使用方法： 下载运行软件：

````
wget https://raw.githubusercontent.com/picgo91/gqxt/main/z301 && chmod 777 /root/z301 && ./z301
````


## 管理界面

![管理界面](https://picgo91.cdn456.eu.org/20250830150557755.png)


