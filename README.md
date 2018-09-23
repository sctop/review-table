# review-table
适用于软件/游戏的评测表格，自适应架构，独立开发

***

## What is this
这是一个由[我](https://github.com/sctop/)开发的一个表格，为评测而生。它包含了基本信息、软件截图、评分等多功能。使用Adobe Dreamweaver开发，历时近三天，属于新手试水作。表格最小支持宽度为360px，完美支持iPhone X的宽度（MMP就差了15px）。是一个非常简单直白的表格。具备加载速度快、兼容设备多的特点，而且为开源软件，任何人皆可使用。

使用了纯HTML5和CSS3，Easy for you and easy for use.

只需要引入一个css文件和html代码，然后就可轻松开始——愉快的体验。

## 开发历程
在一开始我只是想做一个适应[我的博客](https://www.zhangqirun.cn/)的表格样式。于是，我便开始了我的开发之路。

在开发的过程中，自适应是一个难题。因为在我学过的东西中，**没有讲关于如何自适应的**。这件事让我极其脑疼，因为若不同的设备访问，会出现需要上下左右滑动的情况，即把一个大的东西强制塞入了一个小的东西里，然后溢出了。到了后面，我终于发现，其实只要把height和width全部设置成100%就可以了。于是，自适应搞定。

下一个是手机端问题。我本以为在360px附近没什么手机了，毕竟三星的盖乐世S3也没这么小嘛！但是突如其来的一部手机的宽度亮瞎了我的眼睛，它就是iPhone X。iPhone X，竖屏屏幕宽度只有375px，只整整多了15px，图片显示的非常小。于是我便开始用@meida控制，但是后来发现用@media根本控制不了，会冲突，而且taptap的缩放比我这个差多了，然后我便放弃了这个想法。此时是09/23上午了。

开发到90%的时候，我突然改变主意了，我要将这个开源，让这个简单、简洁、即插即用和所有人皆可用的表格运用到网站上。因为首先它是轻量级的，而且由于大部分博客的网站都是白色/灰色背景，非常搭配，所以我便开源了。

## Issues / Pull Requests
你可以提问：

- 自适应问题
- 显示问题（例如在Firefox和Google Chrome上的显示模式的bug）
- 插入问题（无法加载到你的网站）
- 冲突问题（扰乱了网站的布局，可直接PR）
- 代码问题（注：这个可以直接提交PR）

你可以提交PR：

- css样式更新（不要破坏简洁）
- 代码简洁（但不要破坏可读性）

## 开发者的联系方式
请访问https://www.zhangqirun.cn/about.html 获取更多

## 更新日志

20180923 上传源码

### 预计下一版本更新

评分机制，将在biaozhun.md中说明