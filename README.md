# awesome-URLSchemes
> a collection for iOS URLSchemes

**非常欢迎大家提pull request 或者 issue 来提交你知道的scheme**


## 关于

URLScheme 是作为 App 之间跳转的一种常用的手段。目前绝大部分的 App 也都支持。自从有了 Widget 之后，也出现了很多 Luancher 可以帮助你快速的启动 App 或者 执行 App 内部的某个动作。于是就有了这个列表，尽可能的收集目前支持 URLScheme 跳转的 App 所支持的 URLScheme 的情况。以方便您快速使用 URL Scheme 去构建一些更有效率的东西。


## 怎么使用

Awesome-URLSchemes 是一个大集合他可以帮助您快速找到一个 app 支持的 URLScheme 并构建一个 URL 取执行特定的动作例如：

1. 打开某些App
2. 开发某些APP的特定页面
3. 在固定时间打开某些 App
4. ....

## 介绍

* [URL Schemes 使用详解](https://sspai.com/post/31500)

## 内容

* 系统
* 应用



## 系统

> iOS 10 把之前 prefs 开头的 URL Schemes 改成了 Prefs 开头。如果是 App 调用，可添加“App-”前缀。

* 电池电量 Prefs:root=BATTERY_USAGE
* 通用设置 Prefs:root=General
* 存储空间 Prefs:root=General&path=STORAGE_ICLOUD_USAGE/DEVICE_STORAGE
* 蜂窝数据 Prefs:root=MOBILE_DATA_SETTINGS_ID
* Wi-Fi 设置 Prefs:root=WIFI
* 蓝牙设置 Prefs:root=Bluetooth
* 定位设置 Prefs:root=Privacy&path=LOCATION
* 辅助功能 Prefs:root=General&path=ACCESSIBILITY
* 关于手机 Prefs:root=General&path=About
* 键盘设置 Prefs:root=General&path=Keyboard
* 显示设置 Prefs:root=DISPLAY
* 声音设置 Prefs:root=Sounds
* App Store 设置 Prefs:root=STORE
* 墙纸设置 [Prefs:root=Wallpaper](Prefs:root=Wallpaper)
* 打开电话 [Mobilephone://](Mobilephone://)
* 世界时钟 Clock-worldclock://
* 闹钟 Clock-alarm://
* 秒表 Clock-stopwatch://
* 倒计时 Clock-timer://
* 打开相册 Photos://
* 日历 calshow://
* 备忘录 mobilenotes://


## 应用

### 微信

> 在 微信 6.3.25 版本中，所有外部唤起 URL 的方式均无法打开对应页面。 未来这些 url 都只能在微信内部的浏览器使用了。


前缀 **weixin://**

* 唤起 weixin://
* 扫一扫 wexin://scanqrcode


### 支付宝

前缀 **alipay://**

* 唤起 alipays://
* 滴滴出行 alipays://platformapi/startapp?appId=20000778
* 蚂蚁庄园 alipays://platformapi/startapp?appId=66666674
* 收款 alipays://platformapi/startapp?appId=20000123
* 转账 alipays://platformapi/startapp?appId=20000221
* 股票 alipays://platformapi/startapp?appId=20000134
* 扫一扫 alipayqr://platformapi/startapp?saId=10000007
* 记账 alipay://platformapi/startapp?appId=20000168
* 蚂蚁森林 alipay://platformapi/startapp?appId=60000002
* 手机充值 alipayqr://platformapi/startapp?saId=10000003
