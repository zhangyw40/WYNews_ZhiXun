WYNews_ZhiXun
=============

OverView

--------
###新闻首页
![home_news](https://github.com/Roylee-ML/WYNews_ZhiXun/blob/master/ScreenShots/screenshot_1.gif)
###视频
![videos](https://github.com/Roylee-ML/WYNews_ZhiXun/blob/master/ScreenShots/screenshot_2.gif)
###电台
![FM](https://github.com/Roylee-ML/WYNews_ZhiXun/blob/master/ScreenShots/screenshot_3.gif)

项目介绍
-------

1.这个项目是初学iOS时模仿网易新闻写的，实现了视频音频等功能。由于初学，网络请求、视图布局逻辑都相对简单！网络处理也并没有用第三方[`AFNetworking`](https://github.com/AFNetworking/AFNetworking)等，数据请求相对简单，直接定义抓取网易的URL请求数据，也并未做HOST的定义，参数接口的实现。视图布局也是比较简单，自定义`view`用的也不多，后期可以针对性的局部优化。`AutoLayout`方面新增加[`Masonry`](https://github.com/SnapKit/Masonry)添加约束。<br />
2.由于最近公司的项目中做到了视频播放，所以`2.3`版本就对视频播放做了升级改动，播放器进行新的封装优化。视频cell的布局也采用新的方式布局。其中`VideoViewController`在这个版本中弃用，改用`VideoMainPlayControler`代替。同时，视频列表的布局根据网易新闻最新版本做出修改（暂时不支持评论，分享功能），增加顶部视频分类。


总结
----
本项目数据完全抓取网易新闻，放在git上作为交流学习之用，希望同样初学iOS的同学们能够在这条黑道上坚持到底，不断提高自己。
