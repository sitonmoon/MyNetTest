# MyNetTest

https://zhuanlan.zhihu.com/p/139286878  
UE4的GamePlay框架是一个庞大的架构，我制作了一个较小的项目分享给大家。 本项目使用20%蓝图和80%c++制作完成。项目使用UE4-4.24.3制作。

包括：

简单的创建Session、查找Session、加入Session。  
房间人数不足等待其他玩家加入，房间玩家数量足够再开始游戏。  
如果房间人数已满，则无法再加入此房间。  
所有玩家准备就绪，显示开始游戏倒计时。  
所有玩家血量UI同步显示。  
设置玩家出生位置。  
同步显示每个玩家不同的UI颜色、角色颜色。  
如果只有一位玩家存活，游戏结束。如果有一位玩家血量已满，游戏结束。  
游戏结束，所有玩家显示对应UI。  
