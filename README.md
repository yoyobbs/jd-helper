# jd-helper

京东日常小助手, 省时省力

## 目的

浇树啊, 投食啊, 动画时间太长了, 忍受不了

__最近各大电商都在搞类似种树,养宠物换水果或其他奖励的活动, 不巧的是, 女朋友很热衷这些东西, 看她每天游走于各大电商APP小程序之间, 做任务, 浏览店铺, 签到, 简直是太麻烦了, 所以弄了这么个东西__

__分享出来是希望大家能用节省下来的时间, 做一些其他的事情, 例如多陪陪身边人, 健一会身, 读读书, 或者其他方面来提升自己__

__运行在浏览器中的Js, 代码很烂, 将就一下吧__
## 使用方法

__建议使用Chrome浏览器__

#### 步骤
1. 打开chrome, 按下`F12` 或 `鼠标右键检查` 或`Ctrl + shift + i` 打开控制台

2. 切换成手机模拟器形式, 如图:

	![image-20200604235412192](https://ccliuxy-image.oss-cn-beijing.aliyuncs.com/image-20200604235412192.png)

3. 地址栏输入京东移动端的网址`https://m.jd.com/`, 然后登录你的京东账号

4. 控制台tab切换至__Sources__, 找到snippets选项卡, 新建一个snippet文件. 名字随便起个

![image-20200604235312337](https://ccliuxy-image.oss-cn-beijing.aliyuncs.com/image-20200604235312337.png)

5. 看下此项目的子目录, 找到你要执行哪个JD活动的任务, 将其目录下的js文件中的代码全部复制到刚刚新建的snippet文件中, 我这里以jd_pet为例, 粘贴过后请`ctrl + S`保存一下

	![image-20200604235747304](https://ccliuxy-image.oss-cn-beijing.aliyuncs.com/image-20200604235747304.png)

6. 鼠标右击jd_pet文件, 选择Run, 查看控制台领取结果吧!

	![image-20200604235943453](https://ccliuxy-image.oss-cn-beijing.aliyuncs.com/image-20200604235943453.png)

## 重要

__本项目仅限学习交流使用,  不得用于商业用途或非法牟利, 产生一切不当后果与原作者无关__

## 感谢

[zarkin404/sweater](https://github.com/zarkin404/sweater)

原本我是放在服务端自用的, 因为jd的api都需要cookie,避免不了登录, 放在服务端大家用着也不放心, 会有人担心账号安全问题, 无意间看到了__zarkin404__同学的__羊毛衫__, 发现放在浏览器中执行, 就没有任何问题了, 也能放心的分享出来了啦