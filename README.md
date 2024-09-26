# 为什么会有这个网站

<img src="https://i.ibb.co/fDT7Gmc/logo.png">

&emsp;&emsp;很高兴您能够来到我的博客，很久就想拥有个自己的博客平台，能将自己所学积累、运维笔记进行系统梳理并记录，与大家交流分享互通有无方能学有所长，让我们每天进步一点点，好好生活着，每天做着有意义的事，引用《士兵突击》的话：在想要和得到中间还有两个字，那就是要做到，脚踏实地并且为做到付出努力吧！最终我们都能到达自己想成为的样子，不积跬步，无以至千里，致知力行，始于足下 ，就从现在开始吧 ~ ~

> <img src="https://i.ibb.co/GcZ9WQy/20240922170354.jpg" alt="里尔克" style="zoom: 20%;" /> 



**<font size=5><font color=green>本博客网站设为十项运维笔记，标题内容会陆续补档，网站会持续更新，欢迎收藏品鉴！</font></font>**

# 一、工具软件收藏

 ## 1.工具软件收藏Linux

#### [1.Windows下７款我喜欢的监控主机存活软件工具推](https://mp.weixin.qq.com/s?__biz=MzI2MjUzMzU2MQ==&mid=2247483710&idx=1&sn=341f5b24421f39b0bd1f9027502de0bb&chksm=ea48f9e8dd3f70fe301ec645f516a8a6996d56bf32c64407fb4ff0671d076fb6c3b9c316bdb7#rd)

 ## 2.工具软件收藏windows

# 二、实施部署手册

#  三、虚拟化容器化数据库分享

  ## 1.虚拟化技术
  ## 2.容器化技术
  ## 3.数据库技术

# 四、网站维护技术分享

##　1.应用软件维护

#### [1.维护网站点播mp4视频、解决加载缓慢和黑屏视频只有声音问题](https://mp.weixin.qq.com/s?__biz=MzI2MjUzMzU2MQ==&mid=2247483716&idx=1&sn=7f8ad39a69f9750c56679b2e6169fd9a&chksm=ea48f992dd3f7084cb05c30187c89cd7f513e65a821173a2d8b3f265048fc859b228344f647d#rd)

##　2.主机硬件维护

# 五、音视频技术分享

## 1.音频类

 ##　2.视频类

#### <a id="ffmpeg.bat"> [1.利用windows批处理bat文件快速执行视频转码](https://mp.weixin.qq.com/s?__biz=MzI2MjUzMzU2MQ==&mid=2247483734&idx=1&sn=a15fda0ffdd27da10fcf844efc07c5cb&chksm=ea48f980dd3f70967ef115758ba58a3a22f1ea0383b8812c4a11b90fc3424c0db58af4efbc8f#rd)</a></a>

##　3.图像类

# 六、办公技巧分享

# 七、实用脚本收录

  ## 1.实用脚本Linux
  ## 2.实用脚本windows

1.下载的ffmpeg.exe拷贝到C:\Windows\System32下，将下面代码另存bat文件，详情查看<a href="#ffmpeg.bat">五类-2.视频类1节(ctrl+鼠标左键点击跳转文章)</a>

```
@echo off&setlocal enabledelayedexpansion
title 正在转换,mp4转换完成自动关闭
ffmpeg -i %1 -y -qscale 0 -vcodec libx264 %~n1.mp4
for /f "delims=" %%i in ('dir /s/b *.*') do (
    set "foo=%%~nxi"
    set foo=!foo: =!
    set foo=!foo: =!
    ren "%%~fi" "!foo!")
```



# 八、问题排查收录

## 1.问题排查Linux
## 2.问题排查windows

#### [1.记录解决安装VMware报错Microsoft Runtime DLL安装程序未能完成...](https://mp.weixin.qq.com/s?__biz=MzI2MjUzMzU2MQ==&mid=2247483760&idx=1&sn=191e4f693a5389ac37e061d763c400fd&chksm=ea48f9a6dd3f70b0a7fac27e16ed593a8b56b9189d9ef0c1c3e1908062b74198ed22f41ca21f#rd)

# 九、研究指标监控笔记

## 1.指标监控Linux
## 2.指标监控windows

# 十、运维服务参考笔记







