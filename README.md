# WXMDL
WXMDL (WeChat Multi-Domain Login / 微信多域名登录)

微信登录只能设置一个回调域名，而且不能设置顶级域名。
这个插件可以修正多域名调用的问题，目前是专门针对插件 Open Social 做的，理论是支持所有类似需求的。

插件特点：

1、无需做任何设置，上传至微信设置的授权域名的根目录，如：wx.abc.com
2、设置 Open Social 微信的回掉地址为：http://wx.abc.com/wxmdl.php
