Python多环境安装

2017-07-03 邵利民 平庸的逆袭
 一、安装python   
首先我们需要安装两个环境，我这里面安装的是python2.7.13，python3.5.1,正常安装完两个环境
二、配置环境变量


D:\python3;D:\python3\Scripts
D:\python2;D:\python2\Scripts
环境变量之间用分号隔开;

三、修改名称


配置完环境变量之后，我们需要修改名字，进入python2环境中，把    python.exe修改成python2.exe,同理进入python3环境中python.exe修改成python3.exe

四、测试是否安装成功


我们打开cmd命令行，直接输入Python2，或者Python3,看到以上的情况，就代表成功

五、如何安装模块
如果用python3，进入命令行，输入python3 -m pip install  模块名
如果用python2，进入命令行，输入python2 -m pip install  模块名
查询已安装模块
python2或3 -m pip list
