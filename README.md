# FinalProject 
## 作者：沈嘉絮
  
## APP介绍
该APP是以搜索+浏览+信息流为主体功能的Android APP,可以实现对新闻的浏览、搜索，同时用户发布新闻的功能。此外能查看天气预报，观看视频。
## 功能介绍
### 1. 主页模块
#### 1.1 天气
天气图标通过补间动画实现透明度变化功能（Animation实现）

![./image/code1.png](https://markdown.liuchengtu.com/work/uploads/upload_ee749e830adeb29d1d87496454150f7d.png)

点击天气图标，跳转至天气预报界面，24小时和10日天气预报以水平滚动条实现


![./image/code2.png](https://markdown.liuchengtu.com/work/uploads/upload_2e0c53317135bf8cd8e9cc71389b2dd6.png)

![./image/weather_detail.png](https://markdown.liuchengtu.com/work/uploads/upload_6d945c9e887fd5f21f7a466c88bb947d.png)

#### 1.2 发布新闻
点击发布图标进入输入界面，输入标题、正文，可从本地相册选取上传的图片


![./image/code3.png](https://markdown.liuchengtu.com/work/uploads/upload_e56603b4f3b580223c4d531b75eb3e14.png)

![./image/publish.png](https://markdown.liuchengtu.com/work/uploads/upload_5d8c1572607c126e59a1347408703dc7.png)


点击发布按钮后发布，跳转至显示页面

![./image/code4.png](https://markdown.liuchengtu.com/work/uploads/upload_d380922a86c35ca3c777ee2acdec8cb3.png)

![./image/publishNews.png](https://markdown.liuchengtu.com/work/uploads/upload_90f4eeb2b4b57c06eeb18eb5e891e814.png)

#### 1.3 搜索新闻
在文本框中输入新闻作者的名称，可查询相关新闻，如果没有该作者的新闻，则做出提示

![./image/search.png](https://markdown.liuchengtu.com/work/uploads/upload_ef0c18729acd02c3ae683699713e380a.png)

![./image/code5.png](https://markdown.liuchengtu.com/work/uploads/upload_ab1b4964b7d55f70a103229ccdc420c5.png)

#### 1.4 新闻列表

列表采取适配器进行实现，同时实现了文字省略功能，点击每个新闻可进入详细页面浏览

![./image/code6.png](https://markdown.liuchengtu.com/work/uploads/upload_cdb93ac348c14ab438cccae33582ce8f.png)

![./image/news.png](https://markdown.liuchengtu.com/work/uploads/upload_eea06f6d59a00780c423e2a8c4a03b0b.png)


### 2. 视频模块
#### 2.1 视频播放
通过播放、暂停按钮或者直接拖动视频进度条操作视频，也可选择全屏播放观看

![./image/code7.png](https://markdown.liuchengtu.com/work/uploads/upload_871cc57b3f45fd7d7d74002e0cf7ef30.png)

![./image/code8.png](https://markdown.liuchengtu.com/work/uploads/upload_1f2be2f63985afd5b8d1cd7c7c526a96.png)


![./image/fullScreen.png](https://markdown.liuchengtu.com/work/uploads/upload_648f47e324e9a4fa3764e5dc284b50d5.png)


![](https://markdown.liuchengtu.com/work/uploads/upload_648f47e324e9a4fa3764e5dc284b50d5.png)
#### 2.2 视频点赞
点击红心，对视频进行点赞

![./image/code9.png](https://markdown.liuchengtu.com/work/uploads/upload_448f1a7ace08bcad43a3365d6f638688.png)

![./image/play.png](https://markdown.liuchengtu.com/work/uploads/upload_fd1bf3108ec4ca0723ca048d2e1451fd.PNG)

### 3. 我的模块

  ![./image/my.png](https://markdown.liuchengtu.com/work/uploads/upload_d0b905a0a51b25686c43775e8b80da3a.png)
  
## 使用说明
  
1. Gradle Version 8.0
2. Compile Sdk Version 33
3. 直接运行即可
   