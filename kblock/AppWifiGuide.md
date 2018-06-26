# App wifi使用

KBlock APP支持两种方式让wifi模块连接上您的路由器，分别是通过连接wifi模块的热点或者使用smartconfig模式进行配置

## 连接wifi模块的热点

请确认当前wifi模块没有连接到其他路由器热点并处在ap模式，具体判断方法为检查wifi模块的连接指示灯是否**3秒常亮，之后闪烁一下**

进入手机的系统设置并找到wifi模块的热点，通常以**ESP_XXXXXX**的格式出现并且没有连接密码。将手机连接上之后，回到app点击wifi直连配置按钮，并按照提示输入您的路由器名字和密码。

连接成功后，Wi-Fi模块会进入sta模式，并关闭自身的热点。连接指示灯会变成**3s长灭，之后闪烁一下**。这时候您需要将手机切换回您的路由器，回到app后会自动搜索到新的wifi模块。

您也可以使用笔记本或者平板电脑连接上wifi模块的热点，并在浏览器打开http://192.168.4.1 进行配置

## SmartConfig模式

您也可以通过SmartConfig模式将wifi模块加入您家中的路由器，与第一种方法不同的是smartconfig模式不需要切换手机的wifi连接。

**首先请确保您的手机当前连接的是路由器的2.4G热点**

很多现代路由器都有5G和2.4G双频点，但是wifi模块只能连接到2.4G的频段。

给wifi模块通电并确保其在ap模式，其连接指示灯**3秒常亮，之后闪烁一下**

将wifi模块上的开关拨到特殊模式，您可以看到连接指示灯进入**快速闪烁模式**

这时候回到app的wifi连接配置面板并点击smartconfig按钮，按照提示输入您的路由器密码。

稍等片刻后wifi模块如果成功连接路由器后，连接指示灯会**停止闪烁**

最后记得将wifi模块上的开关拨回正常模式，并建议将wifi模块拔下来再插回去以重启。

这是您可以在wifi连接列表中找到新加入的模块










