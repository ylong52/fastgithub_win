GitHub作为程序员访问最频繁的网站，程序员们经常需要访问Github找开源项目、学习新框架、管理自己的个人开源项目等等。因为GitHub属于国外的网站，直接访问的话，速度非常慢，甚至访问不了，今天给大家推荐FastGitHub这款开源项目可以很好的解决国内程序员访问GitHub的困扰，下面来给大家进行介绍，希望对大家的实际工作能够提供帮助！

FastGithub 是 GitHub 访问加速神器，主要解决 GitHub 打不开、用户头像无法加载、releases 无法上传下载、git-clone、git-pull、git-push 失败等一系列问题。


一 安装及使用

解压下载的zip包, 将文件夹放到合适位置

找到FastGithub.UI.exe, 双击执行即可

1. 在访问GitHub前需要打开并保证Fast GitHub在运行状态（需要先运行一会）
2. 在安装完成之后可以直接点开FastGithub的执行文件就可以运行程序，就可以顺利连接到Github

二、访问加速原理
• 修改本机的 dns 服务指向 FastGithub 自身
• 解析匹配的域名为 FastGithub 自身的 ip
• 请求安全 dns 服务 (dnscrypt-proxy) 获取域名的 ip
• 选择最优的 ip 进行 ssh 代理或 https 反向代理