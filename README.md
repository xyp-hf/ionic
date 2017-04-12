# ionic
AngularJS &amp; Ionic入门

# Ionic启动配置

验证是否安装node
node -v

安装Ionic和Cordova
npm install -g cordova ionic

检查ionic和cordova是否被成功安装
cordova -v

更新ionic和Cordova不到万不得已，不更新
npm update -g ionic
npm update -g cordova

创建模板项目
ionic start chapter2
cd chapter2

在浏览器预览
ionic serve

安装安卓SDK
http://developer.android.com/sdk/index.html
如果你打不开，可以访问我的网盘吧
http://pan.baidu.com/s/1qYhQ0X2

点击运行SDK Manager.exe

配置
Android SDK Tools
Android SDK Platform-tools
Android SDK Build-tools(选择最新版本)

Android 4.4.2
SDk PlatForm
ARM EABI v7a System Image

设置模拟器的设置参数

Android avd

选择Device Definitions

建议选择Nexus 4或者Nexus 5
,然后点击Create AVD

设置屏幕的大小，分辨率等

设置完成，点击OK

配置链接设备
一个安卓手机
设置>关于>版本号（点击版本号7次，进入开发者选项）

ＵＳＢ调试
设置允许

给项目添加平台
ionic platform add android

在模拟器中预览(启动比较慢，要耐心等待)
ionic emulate android

开启热重载和命令行日志
ionic emulate android -l -c

在移动设备上预览
ionic run android -l -c

构建安卓项目，生成.apk文件
你可以在platforms/android/ant-build目录中找到他
ionic build android
















