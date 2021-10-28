# 上传接口文档地址

（建议使用post，get需要特殊设置）：

http://8.129.146.172/api/uploadFile/swagger-ui.html



## 服务器源码地址：

```
/opt/fileUpload.zip
```

服务器服务启动命令

```shell
cd /opt
./start.sh
```

## 服务器服务启动命令

```shell
cd /opt
./stop.sh
```



## 服务器对应上传目录

```shell
/opt/uploadFile/
```



# nginx相关命令

```shell
配置环境变量（已配置，只是写给你看的）
vim /etc/profile

	profile新增内容
	export PATH=$PATH:/usr/local/nginx/sbin

加载配置
source /etc/profile

重启
nginx -s reload
启动
nginx -c /usr/local/nginx/conf/nginx.conf
关闭
nginx -s quit
nginx -s stop
检查配置是否正确
nginx -t
```

# java相关信息

```shell
配置环境变量（已配置，只是写给你看的）
vim /etc/profile

	profile新增内容
	export JAVA_HOME=/usr/java/jdk1.8.0_171-amd64
	export CLASSPATH=.:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar
	export PATH=$JAVA_HOME/bin:$PATH

加载配置
source /etc/profile

```

