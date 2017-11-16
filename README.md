# SS/SSR去广告规则
* 项目基于CC-BY-SA-4.0协议发布

# 版本解释
* banAD.acl （默认代理）去广告+局域网直连+国内IP段直连+国内常用域名直连+国外代理
* gfwlist-banAD.acl （默认直连）去广告+局域网直连+国外gfwlist列表代理
* onlybanAD.acl （默认代理）去广告+局域网直连+全局代理
* fullgfwlist.acl （默认直连）国外gfwlist列表代理，没有去广告，没有白名单（原版SS可直接复制文件内容使用）
* backcn-banAD.acl （默认直连）去广告+国内IP段代理+国内常用域名代理+局域网直连+国外直连
* nobanAD.acl （默认代理）局域网直连+国内IP段直连+国内常用域名直连+国外代理
* SSR C#规则 gfwlist-user.rule （默认直连）去广告+局域网直连+国外gfwlist列表代理

# 安卓 SS/SSR 去广告ACL规则
* 屏蔽小米手机和魅族flyme rom系统广告
* 国内网站均直接连接
* 国外常用域名后缀均代理！！！
* 屏蔽常用视频网站广告
* 屏蔽常用网站广告、其他流媒体网站广告
* 屏蔽部分应用程序开屏广告
* 屏蔽部分运营商劫持网页弹出的漂浮球广告、流量统计
* 拦截常用应用程序的隐私跟踪、行为分析、数据统计

# ♻️ SS/SSR Download：
* ACL更新地址（**白名单**）：https://gitee.com/zzj0311/ACL4SSR/raw/master/banAD.acl
* ACL更新地址（**黑名单**）：https://gitee.com/zzj0311/ACL4SSR/raw/master/gfwlist-banAD.acl
* ACL更新地址（**全局**）：https://gitee.com/zzj0311/ACL4SSR/raw/master/onlybanAD.acl
* ACL更新地址（**仅GFWList**）：https://gitee.com/zzj0311/ACL4SSR/raw/master/fullgfwlist.acl
* ACL更新地址（**国内代理**）：https://gitee.com/zzj0311/ACL4SSR/raw/master/backcn-banAD.acl
* ACL更新地址（**白名单，无去广告**）：https://gitee.com/zzj0311/ACL4SSR/raw/master/nobanAD.acl
* SSR C# GFWList user.rule ：https://gitee.com/zzj0311/ACL4SSR/raw/master/gfwlist-user.rule

# ♻️ Surge/Shadowrocket Config File Download：
* Surge Config File 更新地址：https://raw.githubusercontent.com/lhie1/Surge/master/Surge.conf
						 或：https://gist.github.com/scomper/915b04a974f9e11952babfd0bbb241a8/revisions
* Shadowrocket Config File 更新地址：https://raw.githubusercontent.com/lhie1/Surge/master/Shadowrocket.conf

📋 教程 / 说明：
* 打开SSR->路由->自定义acl文件->输入下载地址->更新
* 再次更新，点击软件页面底部的更新即可

# 注：
* 参照vokins大神的hosts规则改编，致谢!! https://github.com/vokins/yhosts
* 参照lhie1大神的surge规则改编，致谢!! https://github.com/lhie1/Surge
* 参照scomper大神的surge规则改编，致谢!!https://gist.github.com/scomper/915b04a974f9e11952babfd0bbb241a8/revisions
* 只是为了加速而迁移到国内，为方便我自己使用少量添加常用网站的一个版本，有问题也不要发给我issue，发到原版去！！！！
		
# License		
* CC-BY-SA-4.0
