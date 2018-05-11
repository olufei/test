[TOC]

# 摘要
vsftpd 是“very secure FTP daemon”的缩写，安全性是它的一个最大的特点。

完全免费的、开放源代码的ftp服务器软件

- 高安全性需求
- 带宽限制
- 良好的可伸缩性
- 可创建虚拟用户
- 支持IPv6
- 速率高等。

# 安装vsftpd
1. 检测是否已经安装vsftpd
```
rpm -qa | grep vsftpd
```
2. 安装

```
yum -y install vsftpd
```

3. 启动服务，检测服务状态 

```
systemctl start vsftpd

systemctl status vsftpd

ss -tnl | grep 21
```

4. 匿名访问测试

windows -- xftp
