# ChinaTunnel
一個可以在Android設備上解鎖中國視頻和音樂的軟件。

## Why ChinaTunnel?

ChinaTunnel的開發主要是為了解決以下問題：

1. 很多基於IP的地址驗證，比如QQ音樂，騰訊視頻，在DNS服務器上是沒有辦法實現的，所以你使用DNS服務器無法正常解鎖這些網站。

2. DNS僅僅適用於WIFI網路，在移動3G情況下沒法起效；

3. 在工作環境中，比如大的工作單位和學校是禁止使用DNS代理的，在這種環境中DNS也是無效；

4. 設置DNS以後，你每次請求都來自DNS我們的DNS服務器，所以提供給你的DNS請求不是最優的，比如你用DNS看bilibili會非常慢。

所以，在這些情況下，ChinaTunnel才進入我們的開發計劃，相比於DNS服務器，ChinaTunnel有以下幾個優點：

1. 原則上如果提供有可以解鎖的Link,不管是基於域名的還是IP的，Chinatunnel都可以解鎖；

2. ChinaTunnel在任何網絡中，WIFI和3G、4G環境下都可以用。

3. 在工作環境和大學環境中，Chinatunnel可以抵抗你們網路管理人員的干擾，保證解鎖順利完成。

4. ChinaTunnel只會干預需要解鎖的link，對不需要解鎖的你仍然訪問的是你本地的離你最近的服務器，保證你訪問不需要解鎖的網站的時候依然有最快最穩定的網速。

## How to use： 首先你的設備必須可以獲取root權限，否則切勿安裝。

1. 從Goolge Play下載本軟件安裝版，或者在Gooogle play搜索ChinaTunnel並安裝。

2. 運行ChinaTunnel後請首先點擊右上角的黃色圖標更新系統白名單，當提示更新完成後再進行其他操作。如果更新失敗重新更新一次即可。

3. 一般情況下，你只需點擊黃色圖標旁邊的開關，向右滑動啟動ChinaTunnel即可，當提示ChinaTunnel運行成功後，按手機上的Home鍵退回到主界面，選擇視頻既可以觀看，ChinaTunnel會在後臺自動解鎖。

4. 如果您想一開機就啟動ChinaTunnel，請在ChinaTunnel上選中開機啟動項。

5. 關於標準模式(standard mode)和省電模式(lite mode)的區別，標準模式是正常的解鎖模式，理論上只要配置好白名單，可以解鎖任何視頻和音樂，包括DNS限制，IP限制以及域名混淆以及https加密等的視頻和音樂網站。但是標準模式雖然強大，會有點耗電；如果你在手機上用，想省電可以選擇省電模式(lite mode)。經多次測試省電模式僅僅會消耗電池電量的0.03%，耗電量幾乎可以忽略。

6. 關於自定義服務器，如果你在中國有自己的服務器，可以配置自己的http代理服務器。但是自己配置服務器僅能標準模式支持。

7. 不要把Chinatunnel其他解鎖方案同時運行，尤其是不要把Chinatunnel和DNS解鎖服務器同時配置。如果你安裝了Chinatunnel，請把您的DNS設置為默認。


## 一些需要註意的問題：

1. 有些用戶在root的時候使用的是360的root工具，或者Kinguser的root授權工具，這些工具會和chinatunnel有兼容性的問題，主要是原因是因為這些工具在root授權上有bug(推薦用supersu.apk作為root授權工具)，因此如果您的手機root了但是卻無法開啟chinatunnel,請檢查是不是這個原因引起的；

2. 有些手機本身的ROM內核有bug,有此問題的是ROM主要是cyanogenmod制作的nightly ROM，還有更新非常頻繁的魅族手機的ROM。如果您的使用了這兩類ROM，chinatunnel開啟了卻無法解鎖，那一定是ROM內核的問題。請嘗試刷不同的ROM版本，多嘗試幾個版本就會碰到一個沒有bug的ROM了，chinatunnel就可以正常工作了;

如果您使用中有任何問題，或者想增加新的解鎖網站，請在issues裏進行反饋！！

最後，感謝您的支持！

********************************************************************************************************

## Why ChinaTunnel?

ChinaTunnel的开发主要是为了解决以下问题：

1. 很多基于IP的地址验证，比如QQ音乐，腾讯视频，在DNS服务器上是没有办法实现的，所以你使用DNS服务器无法正常解锁这些网站。

2. DNS仅仅适用于WIFI网络，在移动3G情况下没法起效；

3. 在工作环境中，比如大的工作单位和学校是禁止使用DNS代理的，在这种环境中DNS也是无效；

4. 设置DNS以后，你每次请求都来自DNS我们的DNS服务器，所以提供给你的DNS请求不是最优的，比如你用DNS看bilibili视频会非常慢。

所以，在这些情况下，ChinaTunnel才进入我们的开发计划，相比于DNS服务器，ChinaTunnel有以下几个优点：

1. 原则上如果提供有可以解锁的Link,不管是基于域名的还是IP的，Chinatunnel都可以解锁；

2. ChinaTunnel在任何网络中，WIFI和3G、4G环境下都可以用。

3. 在工作环境和大学环境中，Chinatunnel可以抵抗你们网络管理人员的干扰，保证解锁顺利完成。

4. ChinaTunnel只会干预需要解锁的link，对不需要解锁的你仍然访问的是你本地的离你最近的服务器，保证你访问不需要解锁的网站的时候依然有最快最稳定的网速。

## How to use：
首先你的设备必须可以获取root权限，否则切勿安装。

1. 从Goolge Play下载本软件安装版，或者在Gooogle play搜索ChinaTunnel并安装。

2. 运行ChinaTunnel后请首先点击右上角的黄色图标更新系统白名单，当提示更新完成后再进行其他操作。如果更新失败重新更新一次即可。

3. 一般情况下，你只需点击黄色图标旁边的开关，向右滑动启动ChinaTunnel即可，当提示ChinaTunnel运行成功后，按手机上的Home键退回到主界面，选择视频既可以观看，ChinaTunnel会在后台自动解锁。

4. 如果您想一开机就启动ChinaTunnel，请在ChinaTunnel上选中开机启动项。

5. 关于自定义服务器，如果你在中国有自己的服务器，可以配置自己的http代理服务器。但是自己配置服务器仅能标准模式支持。

6. 不要把Chinatunnel其他解锁方案同时运行，尤其是不要把Chinatunnel和DNS解锁服务器同时配置。如果你安装了Chinatunnel，请把您的DNS设置为默认。

## 一些需要注意的问题：

1. 有些用户在root的时候使用的是360的root工具，或者Kinguser的root授权工具，这些工具会和chinatunnel有兼容性的问题，主要是原因是因为这些工具在root授权上有bug(推荐用supersu.apk作为root授权工具)，因此如果您的手机root了但是却无法开启chinatunnel,请检查是不是这个原因引起的；

2. 有些手机本身的ROM内核有bug,有此问题的是ROM主要是cyanogenmod制作的nightly ROM，还有更新非常频繁的魅族手机的ROM。如果您的使用了这两类ROM，chinatunnel开启了却无法解锁，那一定是ROM内核的问题。请尝试刷不同的ROM版本，多尝试几个版本就会碰到一个没有bug的ROM了，chinatunnel就可以正常工作了。

如果您使用中有任何问题，或者想增加新的解锁网站，请在issues里进行反馈！！

最后，感谢您的支持！
