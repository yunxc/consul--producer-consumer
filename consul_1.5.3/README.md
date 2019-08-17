cd 到对应的目录下，使用 cmd 启动 Consul
cd D:\Common Files\consul
#cmd启动：
consul.exe agent -dev        # -dev表示开发模式运行，另外还有-server表示服务模式运行


为了方便期间，可以在同级目录下创建一个 run.bat 脚本来启动，脚本内容如下：
consul agent -dev
pause


启动成功之后访问：http://localhost:8500，可以看到 Consul 的管理界面