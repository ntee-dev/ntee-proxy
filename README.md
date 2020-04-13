# ntee-proxy
explain how to use ntee proxy

#### 使用说明
1. 登录 [ntee proxy](https://www.ntee.io) 主站。
2. 根据流程注册并购买流量套餐。
3. 下载第三方客户端。（[mac surge](https://nssurge.com/)，[clash for windows](https://github.com/Fndroid/clash_for_windows_pkg/releases/download/0.9.5/Clash.for.Windows.Setup.0.9.5.exe)，[clash for android](https://github.com/Kr328/ClashForAndroid/releases/download/1.1.10/app-arm64-v8a-release.apk))
###### 注意：若使用iphone手机，则需要解锁国外apple store才可以下载各类客户端（e.g: surge, shadowrocket)

4. 进入[ntee dashboard](https://www.ntee.io/dashboard), 在右边列表下载对应客户端 config 文件（目前支持 surge 和 clash）。
5. 下载后，载入配置文件到客户端， 以clash for android为例，开启 app，选择Profiles, 点击 new profile，选择刚刚下载的clash配置文件，点击右上角保存，回到Profiles 页面 选中刚刚新建好的配置，回到主界面，点击 Tap to start 开启代理。

#### 非 clash 和 surge 客户端。

如果使用非上述两种客户端，可以自行配置代理。

1. 在[ntee dashboard](https://www.ntee.io/dashboard)找到 proxy username 和 proxy password。
2. 在右边菜单中，选择[click to check all available proxy nodes](https://www.ntee.io/proxy_nodes)
3. 选择需要的节点，然后使用 https 代理方式，并输入对应的节点的 url和端口号，username and password。
4. 保存配置后，开启代理。


### 如何使用 Free Coupon
###### 使用 Free Coupon 可以直接续期套餐一个月，每个coupon每人只能使用一次。

1. 在获得 free coupon code (e.g: K4vbnVjuYj) 后, 登录 ntee dashboard。
2. 确认右下角，当前套餐 （subscribe end at:） 的日期。
3. 在 use coupon 输入框内输入对应的 coupon code，点击 use。
4. 操作后会跳转回 dashboard 页面，如果使用成功，会看到右下方 （subscribe end at:） 增加一个月。

###### 注意，每个 Coupon 都有使用次数限制，如果跳转页面没有特别提示，并且套餐没有增加，则说明Coupon已经不能再使用 或者 输入的coupon不合法。

