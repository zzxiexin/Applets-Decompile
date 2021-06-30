# mp-unpack

基于electron-vue开发的微信小程序自助解包客户端  
> 方便没有技术基础的同学轻松进行小程序的反编译

#### 为什么使用electron来做

上手方便、可跨平台

#### 前置准备：利用模拟器获取小程序包

参考博主的原创文章  
> [以中银E路通小程序为例10分钟带你学会微信小程序的反编译](http://xuedingmiao.com/blog/xcx_unpack.html) 

#### 运行截图  

Mac  
<img src="mp-unpack.png" alt="mac解包截图" width="420" />  

Windows  

<img src="mp-unpack-win.png" alt="windows解包截图" width="420" />

#### 如何使用

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](https://www.npmjs.com/)) installed on your computer. From your command line:

``` bash
# Clone this repository
git clone https://github.com/xuedingmiaojun/mp-unpack.git
# Go into the repository
cd mp-unpack
# Install dependencies and run the app
npm install && cd tool/ && npm install 
```

To pack into an app, simply type one of these:

``` shell
npm run build
npm run build:mac
npm run build:linux
npm run build:win32
npm run build:win64
```

#### 实现微信小程序最新运行环境

- [实现小程序编译和运行环境系列(一)](https://mp.weixin.qq.com/s/OjW7GYrNSq-5ojGC3Qa83g)
- [实现小程序编译和运行环境系列(二)](https://mp.weixin.qq.com/s/f6onZC8AWyqg7GL-e0pFXw)
- [实现小程序编译和运行环境系列(三)](https://mp.weixin.qq.com/s/p9xhv1wxhERAn3LlsFVxHA)
- [实现小程序编译和运行环境系列(四)](https://mp.weixin.qq.com/s/StENBEoEIl2_9PrQYl5xkg)
- [实现小程序编译和运行环境系列(五)](https://mp.weixin.qq.com/s/FMrmmAZoayld19WKW75hyQ)
- [实现小程序编译和运行环境系列(终)](https://mp.weixin.qq.com/s/go4imhKuAXv808c52UyiNg)
- [如何深入分析小程序运行原理？](https://mp.weixin.qq.com/s/ZbUFogydJ1d1wGKIjzc21Q)


  
