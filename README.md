# clash5
https://github.com/2dust/v2rayN/releases v2RayN Software download address；


升级功能
从.Net Framework升级到.Net 6 ; 需要下载安装Microsoft .NET 6.0 Desktop Runtime（https://download.visualstudio.microsoft.com/download/pr/ba2ece7b-686a-4bda-b7d7-8cc3b8964d66/8eee13e44d90345d40c1b262c78aad6a/windowsdesktop-runtime-6.0.12-win-x64.exe）
使用WPF重构界面，支持暗黑主题
使用Sqlite数据库重构数据存储，部分功能可能会比以前存变慢
重新设计Core结构，每个Core有独立文件夹，方便管理，统一在bin文件夹下
guiConfigs文件夹：配置文件存放目录
重新整理服务器菜单
移除分组，合并至订阅中；主界面可方便新增订阅分组
订阅更新时可以正则过滤
路由规则集中增加域名解析策略可选设置
主界面状态栏优化
inbound里面增加routeOnly
增加一键测试延迟和速度
Grps增加更多属性，如需要修改默认值，请直接修改guiNConfig
在设置中移除KCP设置，如果需要请直接修改guiNConfig
添加PAC模式, pac.txt 文件在guiConfigs目录，有能力可自行修改或替换，注意保留关键字__PROXY__
自定义配置可选是否显示日志，解决有些Core显示日志时会断流问题
增加选项：为局域网开启新的端口，如果不需要局域网验证可减少端口数量
增加Tun模式；当以管理员运行v2rayN时，在主界面可以方便开启；同时在设置中有相关选项；使用sing-box-core
