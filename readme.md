# Dalamud插件仓库
请在卫月设置-测试版中添加本仓库链接以获取以下插件的最新版本``https://raw.githubusercontent.com/uiharuayako/DalamudPlugins/main/pluginmaster.json``
目前包含  
## ``Uiharu``的插件：  
### XCount：计算周围玩家数量
支持将玩家数量显示到任务栏，主要功能：  
1. 累计统计功能：周围玩家数量是实时更新的，但是因为同时只能获取到周围最多99个玩家，当周围玩家超过100人时则无法正确计数，开启累计统计后，使用者可以通过在人群周围晃一晃扫描到不同的玩家，来统计到更为精确的数字。  
例如：狩猎时周围有超过200人，就可以在人群旁边飞一飞，等累计计数的数量不再增长或零星增长，就获取到了比较精确的玩家数量
2. 人数警报功能：当周围人数超过你设定的阈值时，向聊天框发送一条命令，比如你一个人在家里搓东西，就可以设阈值为2，周围来人就会提示你。
3. 指定id警报：和上面的功能差不多，检测的不是玩家人数而是id
4. 周围玩家列表：``/xclist``，列出周围玩家的姓名部队服务器等级职业等信息。
5. 冒险者职业监测功能

### XIVHardWareMonitor：硬件监控
1. 显示信息到状态栏
2. 硬件数据超过阈值报警到聊天栏

### XIVFakeNews：愚人节快乐~  
用你设定的id发送消息，这个插件的所有交互都在本地，不会真发到服务器。

### Speak Beaver：语音转文字&语音控制
1. 语音转文字：通过讯飞Api把你说的话发送到聊天栏，**这涉及和服务器的交互**  
2. 语音控制：通过本地的语音识别把你说的关键字转成命令发出来，**这也涉及和服务器的交互**  
第一次使用一定要参阅：[插件主页](https://github.com/uiharuayako/SpeakBeaverDalamud)的API白嫖和设置指南

## 其他开源插件的国服可用版本  
1. Artisan by Puni.sh 汉化 by Yarukon：自动制作
2. AutoAction by moewcorp：自动循环
3. LiteralMapLink by Asvel：文字转地图坐标 Api7 版本

# 更新日志：
## 2023-5-8
- XCount更新0.1.0.4版本：增加冒险者监测功能，修复了一些bug