# Unity问题总结 #
---
## 粒子系统 ##
### 学习资料 ###
1. Unity3d-Particle System系统的学习（一）（二）
[http://www.cnblogs.com/CaomaoUnity3d/p/5515262.html](http://www.cnblogs.com/CaomaoUnity3d/p/5515262.html "Unity3d-Particle System系统的学习")

## 图形学 ##
### 学习资料 ###
1. 渲染路径-实时渲染中常用的几种Rendering Path 
[http://blog.csdn.net/onafioo/article/details/51882109](http://blog.csdn.net/onafioo/article/details/51882109 " 渲染路径-实时渲染中常用的几种Rendering Path ")
2. 关于Unity中Shader的基础认识
[https://www.cnblogs.com/HangZhe/p/7220969.html](https://www.cnblogs.com/HangZhe/p/7220969.html "关于Unity中Shader的基础认识")
3. 三维空间变换 [http://blog.csdn.net/code_xbug/article/details/50659946](http://blog.csdn.net/code_xbug/article/details/50659946 "dx11-三维空间变换")

### 图形学总结 ###
1. 所有的渲染路径的核心都是光照的处理
2. 一.延迟渲染路径不允许渲染半透明物体，因为半透明物体深度没有写入。Unity处理不能渲染半透明物体的限制是通过使用在整个处理过程的结尾使用前向渲染来解决的。它工作的效果相当的不错，这些对象可以向其他物体投射一层阴影，但遗憾的是这些物体无法从其他物体接收阴影。但是不幸的是使用前向渲染的话会造成很多未预期的问题。二.限制是缺乏抗锯齿的支持。三.限制是你只可以使用最多四个删除遮罩。最后延迟渲染不支持关于纹理渲染器的接收阴影的标记。
## 性能分析 Unity profiler ##
### 学习资料 ###
1. Unity性能优化（1）-官方教程The Profiler window翻译 [https://www.cnblogs.com/alan777/p/6115505.html](https://www.cnblogs.com/alan777/p/6115505.html "本文是Unity官方教程，性能优化系列的第一篇《The Profiler window》的简单翻译。")
