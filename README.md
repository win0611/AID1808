# Mycode
###需求
Urbtix
1.自动注册账号，自动登录，几百个账号在这个网站倒计时放票的时候同时下单，速度一定要很快。

2.可以自己选择演出节目，，张数，和价位。有自动刷新功能，登录有时间限制，自动登录，就是没有自动登录，账号离线要有提醒。
，
3.抢成功以后快速自动付款。

###使用技术
python3.6 + selenium + Chrome/PhantomJs

###网站问题
1.需要先获取cookie才能进行访问

2.每个局域网的ip从获取cookie开始计时允许在线的时间15分钟左右

3.允许的在线时间截止系统会提示需要重新获取cookie才能访问，即使是会员登录状态下也是一样的

4.访问频率过高会禁止访问