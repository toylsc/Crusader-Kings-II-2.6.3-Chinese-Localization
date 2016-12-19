# 说明

* 这里是基于52汉化组 2.62 alpha 汉化补丁和52论坛若干补完补丁的强迫症园地，可能会导致游戏爆炸。
* 最终目标是能正常运行的2.62打上这个补丁就能实现完整汉化。

## **注意！**你游是一个魔幻游戏

### 本补丁不是也不可能做精确的历史向补完

* 瑞典蛮子对内亚世系有许多魔改，给草原勇士大量派发野爹，只有一部分知名人物能免于青翠。
* 本补丁的补完部分尽力根据汉文和汉译史书寻找各人本尊或原型，但由于大改历史文件的后果无法预料，因此并未修改任何血缘关系。
* 请将王国风云2视为一个平行世界线，并对**部落穿越、姓氏混搭、女频穿越、换妻派对、德国骨科、舅舅神隐**等现象抱有温情和敬意！ 

## 甩锅声明

**不仔细看[用法](https://github.com/Lolisky/CK2_2.6.2_CN_Fix#用法)打补丁打出问题概不背锅！**

![对方不想跟你说话.jpg](http://p1.bqimg.com/507857/3cca17dc98ebe418.jpg)

## 基于

### 汉化与补丁

* 52汉化组 [2.62 alpha 汉化](http://bbs.52pcgame.net/forum.php?mod=viewthread&tid=72131)

* 核动力火锅 [“发挥2.62尝鲜汉化包最大作用的一些技巧”补丁](http://bbs.52pcgame.net/forum.php?mod=viewthread&tid=72774)

* alanleonhardt [家族名dynasties不完全汉化](http://bbs.52pcgame.net/forum.php?mod=viewthread&tid=72770)

* zlthj520的 [事件汉化补完](http://bbs.52pcgame.net/forum.php?mod=viewthread&tid=72633)

### 提供协助的网友

* vurika 协助补全了蒙古领主，提供了畏兀儿一些历史领主的资料。

## 用法

* **（追新党推荐）实时更新的整合包：** 确认已打上打上52汉化组 [2.62 alpha 汉化](http://bbs.52pcgame.net/forum.php?mod=viewthread&tid=72131) 补丁后，直接将[这个](https://github.com/Lolisky/CK2_2.6.2_CN_Fix/archive/master.zip)整合包解压到游戏根目录覆盖同名文件，一步到位。

* **（伸手党推荐）经简单测试的发布版：**只要有能够运行的2.6.2版CK2，根据情况[这里](https://github.com/Lolisky/CK2_2.6.2_CN_Fix/releases/)下载适合自己的那个包，解压到游戏根目录覆盖。

* **（魔改党推荐）自定义文件：**自己去挑文件覆盖。现在的话，用修改后的文件覆盖对应位置的文件即可。如用[蒙古历史角色列表](https://github.com/Lolisky/CK2_2.6.2_CN_Fix/raw/master/history/characters/mongol.txt)覆盖/history/characters/mongol.txt即可。

  ​

* 由本项目作者们独立补完的文件分布于：

  * common
    * cultures（部分）
    * dynasties（部分）
  * history
    * characters（部分）
  * localization
    * India.csv

## 进度更新

### 12.19 （working）突厥家族名 & 库尔德畏兀儿历史人名

* 以重音字母去掉重音符号的简单粗暴方式去乱码
* 逐渐汉化其中明显阿拉伯化/蒙古化的名字。
  * 注：由于中文互联网缺乏库尔德中古史资料，考虑最终根据人物所属文化用现代阿拉伯语和波斯语人名音译标准方案补完汉化。

### 12.19 蒙古角色名、家族名最后的查遗补缺

* 对历史无载也无同名借鉴的人物做了音译。

### 12.18蒙古家族名汉化补完

* 基于alanleonhardt 大佬的“家族名不完全汉化”，补全了蒙古家族名。有两处无法查实的，取哈萨克斯坦同拼写地名的今译暂代。Telingid暂译为迭列斤，但迭列斤蒙古其实是十八部统称，音近的也里吉斤又已经出现了。怀疑P社又在发明历史。

### 12.18 亚美尼亚、阿兰历史领主

* 瞎JB音译补完。

### 12.17 蒙古历史领主正经补完

* 在2.3.6已经翻译的人名的基础上，基于《蒙古秘史》和中文维基补完翻译。
  * 史书无载的人物，拉丁转写与历史人物一致的，视为同名。
  * 汉文史书无记载，也无法拟合读音的个别人物，主要是一些阻卜人和P社发明的人物，以同时代音译用字音译。
  * **译法取舍整体上尽量忠于原版，尽量不做恶搞。多译法取佳字，个别特殊名字意译。**如：成吉思汗的女儿Khojin Beki，一般译为火臣别吉，由于Beki是美称，理论上也可以译为霍金酱，最终采用了金庸的别译“华筝”。Borte Chino，译为苍狼。Gua Maral，译为白鹿。
  * **单独一个人与史书不同，认为是P社搞错的，以史书为准。**如：成吉思汗宠妃也速干之父也客扯连，P社钦定为Jalibukha/札里不花，按前者。那海（诺盖汗国）妻阿刺忽改为景教徒。

  * **多来源不一致或P社“合理想象”的，基本直译。** 如：蒙哥的皇后有四人说（《史集》）和五人说（《元史》），P社一股脑取了并集，直译。汉文典籍记载蒙哥九个儿子留下了名字，英文维基非要写十个，P社写了十一个，蒙哥 Möngke，忽睹都 Qutughtu，忽必烈 Kublai，旭烈兀 Hulagu，阿里不哥 Ariq Böke，拨绰 Bujek，末哥 Mukha，岁哥都 Satukhtai，雪别台 Sabukhtai之外对应不上的俩，取同名音译。脱古思传说是王汗后代，P社钦定她是桑昆之女、王汗孙女，直译。7500行以后P社各种弃疗瞎攀亲（啊，蛮族的武德把北欧的费拉吸入姨内），直译。

  * 最后，薛出列Semsochule的两个儿子Ardi Barlas、Ang Goran汉文无载，像土耳其语，应该是已经突厥化了，现在凑合译成阿迪 八剌失、安 固兰，请大佬们指正。

### 12.16 印度地名

* 随便改了几处。