# hiumsentences
适用于[HoshinoBot V2](https://github.com/Ice-Cirno/HoshinoBot)的网抑云插件, 会附带随机发图(需额外网抑云表情包). 您可以自行添加表情包, 也可以只发送纯文字. 

本项目GitHub地址：https://github.com/pcrbot/hiumsentences

Gitee地址：https://gitee.com/varmixer/hiumsentences

自用静态资源库地址(不保证更新): https://gitee.com/varmixer/res

语录来源: http://api.heerdev.top/nemusic/all

## 指令与功能
以下关键词触发:
上号, 生而为人, 生不出人, 网抑云, 已黑化, 到点了

会发送一条网抑云语录加一张表情包, 没有表情包也可以发送纯文字


## 开始使用

1. 切换至模块目录下(请自行根据实际情况修改路径):
   ```
   cd ~/HoshinoBot/hoshino/modules/
   ```
2. 克隆本项目:
   ```
   git clone https://github.com/pcrbot/hiumsentences.git
   ```
3. 在HoshinoBot的静态资源库下, 新建目录来存放网抑云表情包, 正确的目录结构:
   ```
   res
   |--img
      |--priconne
      |--chat
         |--网抑云
            |--pic1.jpg(名称任意)
            |--pic2.png(名称任意)
            ......
   ```
   如果您找不到网抑云表情包, 也可以从我自用的静态资源库寻找(链接见开始部分)
   国内链接(码云)


## 其他
* 网抑云语录已本地化, 保存在`nt_words.json`中, 您可依照格式自己进行添加删除等操作(请留意json格式), 其中`"from"`暂时不起用.
* 欢迎按照格式添加语录后, 补充到本项目中, 或贡献表情包也可
* 项目最初来源自酷Q某插件, 现在无法查证, 在此感谢API提供者
* `hiumsentences`是因为最初时一名群友写的就叫这个名字, 重写时懒得改了所以就还叫这个名字了.
