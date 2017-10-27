### 钉钉自动考勤
----

问：你们公司打卡么？

答：我在公司不用打卡！

问：你是公司领导吧？好厉害！

答：你们全家都是领导！！我是在公司扔了一个手机，它会自动打卡 (骄傲脸

----

### 重要提示!!!
* **保证触动精灵总是在前台运行**
* **取消任何屏幕解锁**
* **手机必须处于充电状态**
* **建议上下班多设置几个打卡时间段，以防漏打**

----

### 准备
1. 一台android手机，需要root
2. 数据线和充电插头
3. 安装触动精灵android版, APKs目录里面有安装包
4. 当然如果没有钉钉，你现在也不会看到这儿
    
### 安装方法一：手动

* 安装上(下)班打卡
	* 点击触动精灵左上角新建脚本, 任意命名。如：『钉钉上(下)班打卡』
	* 将项目 `punch-in(out)/main.lua` 文件内容粘贴到脚本中
	* 设置定时运行时间, 如：8：50 (18: 01)
	
### 安装方法二：扫码

* 上班打卡

![上班打卡二维码](./punch-in/qrcode.png )

* 下班打卡

![下班打卡二维码](./punch-out/qrcode.png)


### 真相 57s

<video src="auto-punch.mp4" controls="controls" autoplay muted loop height="500"></video>

### 成功日志

<img src="./punch1.png" height="500">
<img src="./punch2.png" height="500">

### 已测试软件版本

| 钉钉  | 触动精灵 | 手机 |
|:------------- |:---------------:| -------------:|
| v3.5.0+      | v2.2.5 |         SM-N900 |
| v3.5.0+      | v2.2.5 |         GT-i9300 |
| v3.5.0+      | v2.2.5 |         Redmi 4 |
| v3.5.0+      | v2.2.5 |         R8107 |
| v3.5.0+      | v2.2.5 |         LG-D859 |
| v3.5.0+      | v2.2.5 |         Redmi Note 3 |
| v3.5.0+      | v2.2.5 |         MI 4LTE |
| v3.5.0+      | v2.2.5 |         MI 2 |
| v3.5.0+      | v2.2.5 |         Lenovo A808t |

### 脚本定制

* 开发者选项 -> 打开显示触摸操作, 打开指针位置
* 获取『考勤』按钮坐标
* 获取『上/下班打卡』按钮坐标
* 替换脚本里的 `findMultiColorInRegionFuzzy` 方法对应的x和y坐标的值
* 如果有问题，请开issue
* 如果你想联系作者 QQ:33227329

### 如果你想请我一杯咖啡

<img src="./buy-me-a-cup-of-coffee.jpeg" height="300">
