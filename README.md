KM-storechange 
=============== 

KM-storechange是基于Keyboard Maestro系统，用于快速切换mac系统app store账号的宏，所以要使用该宏需要先下载Keyboard Maestro系统，该软件功能强大，可以编写其他的宏来完成很多重复的任务。

该宏暂只支持macOS Mojave（10.14）中文版

===============

注意事项：
1. 导入后会有三个宏，change account作为入口，退出账号；choose account选择需要登录的账号；login store登录账号，记得启用宏，快捷键control+option+command+Y
2. 将appid存到苹果的钥匙串中，可以避免密码泄漏,具体的使用，可查看宏
3. 需要保持账号在choose account宏和钥匙串中一致，参考宏中的html代码（很简单）