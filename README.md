# accessToSsr

@[toc]
# 下载安装包

从 https://github.com/qingshuisiyuan/electron-ssr-backup 下载对应系统的安装包。
我用的ubuntu，所以下了AppImage

AppImage打开方法：

 1. 添加可执行权限
>chmod a+x *.AppImage
 2. 执行
>./*.AppImage

在主界面内 添加--添加订阅地址--更新，选择一条靠谱的线路。
订阅地址从这里找：
https://github.com/ohssr-cf/ohssr/wiki

# Chrome安装Proxy SwitchyOmega

 1. 打开https://github.com/FelisCatus/SwitchyOmega/releases，页面滚动到下方，找到SwitchyOmega_Chromium.crx，点击链接下载crx文件。
 2. 在Chrome浏览器的地址栏输入chrome://extensions/，然后回车，打开扩展程序页面。在这里，无法直接将刚才下载好的crx文件拖进来，需要做一些处理。
 3. 将刚才下载好的crx文件的扩展名改为zip，用解压缩软件解压到目录中。
 4. 在扩展程序页面中，找到右上角的开发者模式，将开发者模式打开。
 5. 在左上角会出现三个按钮，点击“加载已解压的扩展程序”铵钮，打开文件选择窗口，选择刚才解压的目录，然后点击“选择文件夹”按钮。
 6. 这里，插件就已经成功安装进来了，虽然显示有错误，但并不影响使用。这时，在地址栏的边上会显示Proxy SwitchyOmega的图标。
 7. proxy配置参考
protocol : socks5
server: 127.0.0.1
port:   1080
再编辑auto switch

https://jingyan.baidu.com/article/219f4bf7a0b737de442d38e8.html 
