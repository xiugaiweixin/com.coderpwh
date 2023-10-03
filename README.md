# WxRecordRead
<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/Xposed-Modules-Repo/com.coderpwh">


---

## 微信聊天记录wxid读取,消息修改

使用 [YukiHookAPI](https://github.com/fankes/YukiHookAPI)开发
* 代码开源地址[WxRecord](https://github.com/pwh-pwh/wxrecordread)

* 目前支持 仅测试8.0.23,8.0.25 版本 v1.2版本仅支持微信8.0.40版本
* 请使用[WxRecord](https://github.com/pwh-pwh/wxrecordread/releases/tag/v1.1) 以保证支持8.0.23,8.0.25 版本
* 请使用[WxRecord](https://github.com/pwh-pwh/wxrecordread/releases/tag/v2.0) 支持8.0.23,8.0.25 版本(聊天页面消息修改功能)
* v2.1发布支持8.40.0修改消息[WxRecord](https://github.com/pwh-pwh/wxrecordread/releases/tag/v2.1)
* v2.2版本修改：修改信息入口改为点击聊天页面用户名，避免与其他模块冲突[WxRecord](https://github.com/pwh-pwh/wxrecordread/releases/tag/v2.2)
* 暂时提高版本号范围以支持一些不容易改变的类

### 主要功能如下

---

* 获取聊天记录发送消息者wxid
* 修改聊天页面消息(仅从TextView做文字替换处理,暂不支持8.0.40版本)
* 查看红包总额
* 查看红包领取详情
* 注意：消息修改生效时间：比如在和a聊天界面点击修改，修改完后，要退到微信主界面点到其他人如b的聊天界面，然后再回到a就生效了

## 用法

* 点击折叠转发的聊天记录，即可弹出wxid信息
* 长按聊天界面+按钮即可弹出修改功能界面

## 截图

![image](https://pic.rmb.bdstatic.com/bjh/82ea7a148cf2c578346f0999929840bc.jpeg)
![pPO3BJf.jpg](https://z1.ax1x.com/2023/10/03/pPO3BJf.jpg)
![pP79OIO.md.jpg](https://z1.ax1x.com/2023/09/24/pP79OIO.md.jpg)
![pPO3UeA.jpg](https://z1.ax1x.com/2023/10/03/pPO3UeA.jpg)


---

## 常见问题


* 模块初次使用建议操作流程

        1.安装好模块后把模块和微信都强行停止运行
        2.激活(勾选)模块
        3.打开模块配置好相关选项
        4.强行停止模块运行
        5.打开微信

## 注意

* 模块仅供学习，请勿用于非法用途，如有其他疑问，请提issus
=======

## 👏✨

* 觉得有用欢迎✨[WxRecord](https://github.com/pwh-pwh/wxrecordread)
