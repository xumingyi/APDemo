# APDemo
Android WiFi热点完全研究(自定义创建、跳转系统界面设置、读取配置、切换，Android6.0适配)
http://www.cnblogs.com/fly263/p/7341768.html

>Android 6.0/7.0已测试，8.0未测试，Android 8.0已经废弃WifiManager.setWifiApEnabled(WifiConfiguration, boolean)方法，可能需要使用ConnectivityManager#startTethering(int, boolean,* ConnectivityManager#OnStartTetheringCallback)

>布局文件使用了ConstraintLayout，如果没有安装，需要在Android Studio中点击File-Settings-System Settings-Android SDK，切换到SDK Tools标签页，下载ConstraintLayout for Android、Solver for ConstraintLayout两个支持库

# Demo UI
![Demo UI](captures/AppUI.png)
# System UI(From MIUI 9)
![SystemUI1](captures/SystemUI1.png)&nbsp;&nbsp;![SystemUI2](captures/SystemUI2.png)
