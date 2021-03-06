# 个人简历
[![NPM version](https://badge.fury.io/js/yangjunlong.png)](http://badge.fury.io/js/yangjunlong)
> There is only one heroism in the world：to see the world as it is and to love it.

## 自我介绍
> 7年+WEB前端开发经验，主攻前端和PHP开发，有亿级PV产品线项目经验，带领3人团队从零构建一个WEB前端项目，包含了视频播放、地图展示、个人中心等功能。对模块化、组件化、性能优化有一定研究。

## 个人信息
姓名：杨军龙

性别：男

籍贯：山东

职业：`前端开发工程师` · `北京`

## 教育经历
`2006.9` ~ `2010.6` [山东财经大学](http://www.sdufe.edu.cn/) `信息管理与信息系统专业` 本科

## 工作经历
- `2016.5` ~ `至今` [小米](https://www.mi.com/)
	- [x] 负责小米钱包，话费充值、生活缴费等应用开发
	- [x] 封装小米钱包Hybrid jssdk基础库
	- [x] 前端性能(用户行为)数据收集
	- [x] 负责后台系统的前端开发

- `2015.9` ~ `2016.5` [58](https://www.58.com/)
	- [x] 品质公寓项目前端负责人(包括前台房屋信息展示及后台房屋信息录入)，带领团队从零构建
	- [x] 负责项目前端架构，模块化，组件化，组员按模块负责并行开发

- `2012.7` ~ `2015.9` [百度](https://www.baidu.com/)
	- [x] 重构百度经验详细页面
	- [x] 重构百度经验个人中心
	- [x] 百度经验财富商城开发

- `2011.5` ~ `2012.6` [高德](http://autonavi.com/)
	- [x] mapabc地图鱼骨控件编写
	- [x] 基于edojs框架的地图样式编辑器开发
	- [x] 地图API使用手册站点开发

- `2010.7` ~ `2011.4` [普加](http://www.pujia.com/)
	- [x] 公交地图站点数据爬虫编写
	- [x] 自定义地图小工具代码编写
	- [x] jQuery图片轮播插件编写
	- [x] 学会使用svn，linux命令，lamp环境搭建等
	- [x] [Mapbar经纬坐标偏移的加/解密算法](http://sobird.me/latitude-and-longitude-coordinates-offset-will-mapbar-encryption-decryption-algorithm.htm)

## 个人能力
* <del>`具有连续加班到晚11点20天+的经历&能力`。</del> 坑爹~
* 精确实现UE图稿到交互页面
* 熟悉fis-kernel源码
* 熟悉`PHP`，开发了个人框架:[hating](https://github.com/yangjunlong/hating)，语法高亮库:[SyntaxHighLighter](https://github.com/yangjunlong/SyntaxHighLighter)
* 熟悉`Node.js`、`NPM`包开发与发布
* 熟练操作`Linux`系统，通过WEB日志快速定位问题
* 熟练使用`AngularJS`构建SPA(单页面应用)后台系统，开发了框架:[mix-dashboard](https://yangjunlong.github.io/mix-dashboard/)
* 具有团队文档平台建设经验，对前端开发代码`规范化`、`平台化`、`工具化`有一定的探索能力。

## 项目经历
**58品质公寓项目**(2015.12 ~ 2016.1)
> 该项目主要定位：高品质服务式青年公寓，面向20-30岁追求生活品质的白领、留学生、有一定的消费能力的人。

主要工作：
* 基于jello + velocity 前后端分离 并将fis-velocity-tool引入后端，解决前端静态资源自动依赖输出的问题。
* 组件化：地图展示、log统计等，只需在业务场景中`require`进来即可使用，组员无需关心具体实现。
* 跟进项目进度，协调在58APP中的测试工作。

[项目地址](http://gongyu.58.com) 请使用手机查看

**百度经验前端性能优化**(2015.6 ~ 2015.7)
> 自经验前端从fis1升级到fis2后，静态资源打包策略因升级带了一些变化，造成代码冗余，各种项目积累N久，经验前端性能优化势在必行。
该项目是年初经验前端技术规划中隶属前端性能优化中的一部分，最早5月份开始前期调研，6月份给经验主要页面加入资源统计脚本，7月上线。

主要工作：
* 前期调研设计
* 接入《FIS静态资源自动合并系统》自动打包优化。
* 优化common-new模块，主要是从fis1升级fis2遗留的冗余js代码。
* 模板压缩优化 开发完成 《[fis-optimizer-tpl-compress](https://www.npmjs.com/package/fis-optimizer-tpl-compress)》模板压缩插件。
* 根据上平台的打包结果，自测调优后上线各个模块。

[线上预览](http://jingyan.baidu.com/article/6525d4b153c977ac7c2e945b.html) 右键查看源码可看到效果

---

**经验个人中心改版项目**(2014.9 ~ 2014.10)
> 个人中心作为用户的根据地，能够在情感和荣誉上予以用户激励，同时也能让新用户初步了解经验，予以部分转化。此次改版主要针对作者自己看自己，而看别人个人中心则会随之优化。该项目主要提升用户体验，统一经验站内样式。

主要工作
* 前端技术方案选型
* 新接口定义&升级文档整理
* 个人中心消息系统文档梳理

[线上预览](http://jingyan.baidu.com/user/nuc) 需要登录

---

**经验财富商城项目**(2014.3 ~ 2014.4)
> 财富商城项目通过财富值兑换礼品的方式来激励用户进行创作，使得经验财富值得以流通起来，为后续更多元化的激励模式奠定基础，并为后续社区化建设提供虚拟货币的基础。

主要工作：
* 负责项目的前端开发和项目推进工作。
* 设计项目详细设计文档，确定项目排期
* 项目上线收益效果跟进

[线上预览](http://jingyan.baidu.com/shop)

---

**经验详细页面改版**(2013.10 ~ 2013.11)
> 该项目主要对经验详细页进行了一次全新的改版，新版页面更加扁平化，兼容宽屏与窄屏自适应等，改版后的页面用户体验更好，页面性能提升10%左右，PV&UV也有一定量的提升。

主要工作：

* 负责项目的前端开发和项目推进工作，确定项目排期。
* 经验整站导航，款窄屏自适应以及右侧栏目的开发。
* 优化代码，抽象前端公用组件

[线上预览](http://jingyan.baidu.com/article/6525d4b153c977ac7c2e945b.html)

---

**经验回享分成体系项目**(2013.2 ~ 2013.5)
> 该项目在功能上完成用户加入、CPM等级、后台管理、收入计算、收入提现等一整套完整体系，为经验后续提升用户活跃度、用户贡献量等系列激励项目打下了坚实基础，该项目上线取得不错的效果：经验提交量增长100%、每日贡献用户数增长200%、用户的活跃度、平台与用户的交流以及经验的质量都有很大提高。

主要工作：

* 负责整个项目的前端页面开发，需求分解，负责前端详细设计文档、迭代计划。
* 基于FIS抽象前端公用组件。
* 精确实现UE图稿到静态页面，及页面交互细节的实现。
* 后续二期三期迭代跟进开发，项目总结分享。

[线上预览](http://jingyan.baidu.com/user/income)

---

## 联系方式
邮箱：583528957@qq.com

博客：[http://sobird.me](http://sobird.me)

## 最后
如果你觉得我的简历还不错的话，通过支付宝打赏我

<img src="https://raw.githubusercontent.com/yangjunlong/resume/master/assets/weixin.jpg" alt="微信捐赠" title="微信捐赠" />

又或者，你跟我很熟？

<img src="https://raw.githubusercontent.com/yangjunlong/resume/master/assets/zhuang13.jpg" alt="简历求扩散" title="简历求扩散~" width="250px" />

那么，请`速扩散`此`简历`~

#### 彩蛋? :blush:
[前端面试题库](https://github.com/yangjunlong/resume/wiki)

## 致谢
谨在此向所有在我求职过程中帮助过我的小伙伴们表示感谢！

如果你对此简历有任何问题，欢迎提[issue](https://github.com/yangjunlong/resume/issues)。
