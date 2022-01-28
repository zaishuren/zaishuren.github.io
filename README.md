代码
<html><head>
<meta http-equiv="Content-Type" content="width=device-width, initial-scale=0.95, minimum-scale=0.5, maximum-scale=2.0, user-scalable=yes charset=utf-8" name="viewport">
     <meta name="baidu-site-verification" content="code-NyuZIHO0sy">
     <script src="https://cdn.jsdelivr.net/gh/axutongxue/axutongxue.github.io@main/cdn/jquery.js"></script><script src="https://cdn.jsdelivr.net/gh/axutongxue/axutongxue.github.io@main/cdn/seek.js"></script><script async="" src="https://busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script><script src="https://cdn.jsdelivr.net/gh/axutongxue/axutongxue.github.io@main/cdn/RunTime.js"></script><link rel="shortcut icon" href="favicon.ico"><link rel="bookmark" href="favicon.ico"><link type="text/css" rel="styleSheet" href="https://cdn.jsdelivr.net/gh/axutongxue/axutongxue.github.io@main/cdn/style.css"><link type="text/css" rel="styleSheet" href="https://cdn.jsdelivr.net/gh/axutongxue/axutongxue.github.io@main/cdn/myRewards.css"><link rel="stylesheet" href="https://cdn.staticfile.org/font-awesome/4.7.0/css/font-awesome.css"><script src="https://cdn.jsdelivr.net/gh/axutongxue/axutongxue.github.io@main/cdn/dark-mode.js"></script>
</head>
<title>阿虚同学的储物间</title>
<body> <button onclick="changemode();" class="darkmode-toggle--white darkmode-toggle"><span class="fa-stack"><i class="fa fa-sun-o fa-stack-1x"></i><i class="fa fa-moon-o fa-stack-1x"></i></span></button><div id="clickCanvas" style="position:fixed;left:0;top:0;z-index:99;pointer-events:none;"></div><a href="https://axutongxue.com/reply" style="transform: translate(60px,-10px);" class="forkit"><span class="tag" style="transform: rotate(45deg) scale(0.7);">获取公众号设置的自动回复</span></a><div style="text-align:center;margin-top: 15px;"><a id="topSerach" href="https://data.newrank.cn/m/s.html?s=NykqOiw2LjJJPw">搜索公众号历史文章 <i class="fa fa-weixin"></i></a></div><div id="bottomSearch" style="position:fixed;right:0;text-align:center;bottom:20;left:0;background-color:whitesmoke;opacity:0.8;"><input id="complete" type="button" value="完成" style="font-size:16px;margin-right:4px;display:none;" onclick="complete()"><input id="key" type="text" style="width:180px;font-size:16px;" placeholder="输入你想搜索的内容"><input type="button" value="<" style="font-size:16px;margin:0 2 0 6;" onclick="previous()"><input type="button" value=">" style="font-size:16px;margin-left:4px;" onclick="next()"></div>
<ul><ul style="margin-left:-60px;font-size:17px;">
        <li><i class="fa fa-folder fa-lg"></i><a> 01　电影／电视剧／综艺／动漫／纪录片</a>
        <ul class="menu">
            <li><i class="fa fa-folder fa-lg"></i><a> 01.网页　综合（聚合搜索）🔍</a>
            <ul class="menu">
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://7080.wang/" target="_blank"> 🌕7080影视搜（聚合搜索）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://cupfox.app/" target="_blank"> 🌕茶杯狐（聚合搜索）（备用 cupfox.com／有同名公众号）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.dianyinggou.com/" target="_blank"> 🌕电影狗（聚合搜索）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://xsear.ch/" target="_blank"> 🌕未知搜索（聚合搜索）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.yszy5.com/" target="_blank"> 🌕资源影视屋（聚合搜索）</a></li>
                <li id="split" style="color:black;font-size:12px;opacity:0.7;">————————</li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.wuhaozhan.net/" target="_blank"> 🌗五号站（聚合搜索）－PC右下角弹窗广告／手机端半屏弹窗广告</a></li>
            </ul></li>
            <li><i class="fa fa-folder fa-lg"></i><a> 02.网页　综合（在线／下载）</a>
            <ul class="menu">
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://mp.weixin.qq.com/s/Fhr0ji-izW7VNWGh3p2-1w" target="_blank"> 👍针对这类网站广告的解决方案：全平台网页去广告规则+使用教程</a></li>
                <li id="split" style="color:black;font-size:12px;opacity:0.7;">————————</li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://qianoo.cn/" target="_blank"> 🌕厂长资源－无广告－磁力－支持IDM整段下载</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://loli.magedn.com/" target="_blank"> 🌕MaGeDN－无广告－提供蓝光磁力－支持IDM整段下载</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.btsj5.com/" target="_blank"> 🌕BT世界－无广告－电驴－支持IDM整段下载</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://bdys.me/" target="_blank"> 🌖哔嘀影视地址发布页（备用：mp4er.com／bde4.icu）－PC端右下角棋牌广告／手机端无广告－磁力／ed2k</a></li>
                <li id="split" style="color:black;font-size:12px;opacity:0.7;">————————</li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.feijisu8.com/" target="_blank"> 🌗飞极速在线（备用：feijisu6.com／feijisu.com）－PC无广告／手机端新窗口色情广告－百度云</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.bttwo.com/" target="_blank"> 🌗两个BT－PC端无广告／手机端新窗口色情广告－支持IDM整段下载－种子</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.idybee.com/" target="_blank"> 🌗电影蜜蜂－PC端无广告／手机端新窗口色情广告－百度云／磁力－支持IDM整段下载</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.pianku.li/" target="_blank"> 🌗片库（备用：pianku.me）－PC端无广告／手机端底部棋牌广告－磁力－支持IDM整段下载</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.dygang.cc/" target="_blank"> 🌘电影港－大幅背景广告－支持IDM整段下载－磁力／百度云</a></li>
            </ul></li>
            <li><i class="fa fa-folder fa-lg"></i><a> 03.网页　综合（仅在线）</a>
            <ul class="menu">
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://mp.weixin.qq.com/s/Fhr0ji-izW7VNWGh3p2-1w" target="_blank"> 👍针对这类网站广告的解决方案：全平台网页去广告规则+使用教程</a></li>
                <li id="split" style="color:black;font-size:12px;opacity:0.7;">————————</li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://fantuan.tv/" target="_blank"> 🌕饭团影院（TG群：t.me/fantuantv）－无广告－支持IDM整段下载－🆕</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://vip.8kvod.com:888/" target="_blank"> 🌕8K影视 -无广告－支持IDM整段下载</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://dianying.im/" target="_blank"> 🌕电影先生（备用：dianying.in／dianying.im／dianyingim.com）－无广告－支持IDM整段下载</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.dixi123.com/" target="_blank"> 🌕嘀嘻嘀嘻－无广告－支持IDM整段下载</a></li>
                <li id="split" style="color:black;font-size:12px;opacity:0.7;">————————</li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://123456.li/" target="_blank"> 🌖核桃影院（备用：video.tf／htoo.vip）－播放页面广告－支持IDM整段下载</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://yanetflix.com/" target="_blank"> 🌖4K鸭奈飞资源站（备用：4kya.com、netflix.com、netflixya.com）－PC端无广告／手机端播放页面莆田广告－无广告－需用M3U8方式下载</a></li>
                <li id="split" style="color:black;font-size:12px;opacity:0.7;">————————</li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.yatu.tv:88/" target="_blank"> 🌖雅图在线－有游戏广告／未适配移动端－超10年以上站点</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://redianyy.cn/tv.html" target="_blank"> 🌗热点影院－PC无广告／手机底部棋牌广告－支持IDM整段下载－🆕</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://dsxys.com/" target="_blank"> 🌗大师兄影视（TG群：t.me/joinchat/R-1Nfm1p9tXrDi9C）－PC端横幅广告／手机端底部色情广告－部分线路支持IDM整段下载</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.jiujiukanpian.com/" target="_blank"> 🌗久久影视网－PC端无广告／手机端底部色情广告－支持IDM整段下载</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.o8tv.com/" target="_blank"> 🌗555电影－PC端无广告／手机端播放页面棋牌广告／支持IDM整段下载</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.naisitv.com/" target="_blank"> 🌗奈斯TV－PC端无广告／手机端底部色情广告－支持IDM整段下载</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://susudm.com/" target="_blank"> 🌗速速电影院－PC无广告／手机端底部色情广告－支持IDM整段下载－🆕</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://gimy.app/" target="_blank"> 🌗Gimy TV 剧迷－PC无广告／手机端播放页面色情广告－支持IDM整段下载－🆕🔗</a></li>
                <li id="split" style="color:black;font-size:12px;opacity:0.7;">————————</li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.zhenbuka3.com/" target="_blank"> 🌘真不卡影院（发布页：zhenbuka.fun）－有大面积广告－需用M3U8方式下载</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.nfmovies.com/" target="_blank"> 🌘奈菲影视（TG群： https://t.me/joinchat/KmUaGRMWdO29JVd3wcCHCg）－大面积广告且会要求关闭屏蔽广告－支持IDM整段下载</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.dudu2020.com/" target="_blank"> 🌘嘟嘟电影网－有大面积广告－支持IDM整段下载</a></li>
            </ul></li>
            <li><i class="fa fa-folder fa-lg"></i><a> 04.网页　综合（仅下载）</a>
            <ul class="menu">
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.rrdynb.com/index.html" target="_blank"> 🌕人人电影（备用：rrdyw.net、rr2023.com、rr2022.com）－阿里云／百度云／迅雷云🆕</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.yinfans.me/" target="_blank"> 🌕音范丝（蓝光））－磁力🆕</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://ppxzy.cc/" target="_blank"> 🌖皮皮虾资源－提供百度云／阿里云盘🆕</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.xijing.tv/movie/index" target="_blank"> 🌕戏精TV－百度云－支持RSS🐢</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.uump4.net/" target="_blank"> 🌕悠悠MP4－提供磁力／电驴／种子</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.xiaohx.org/" target="_blank"> 🌕小浣熊（蓝光）－磁力</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://258.tv/" target="_blank"> 🌕爱我吧（蓝光）－磁力</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://ifenpaidy.com/" target="_blank"> 🌕分派电影－提供迅雷网盘</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.xunleicang.in/" target="_blank"> 🌗迅雷仓－磁力</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://yyds.fans/index" target="_blank"> 🌕YYDS电影－迅雷／百度／阿里云盘／115🐢</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.dlkoo.cc/" target="_blank"> 🌕大连生活网（备用dlkoo.com／dlkoo.me）－百度云</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.jsr9.com/" target="_blank"> 🌕BT天堂－提供磁力</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.hao4k.cn/?fromuid=515573" target="_blank"> 🌕Hao4K影音（蓝光）－磁力</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.hao6v.net/" target="_blank"> 🌖6V电影（备用：hao6v.com／6vhao.tv）－磁力</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.ck180.net/" target="_blank"> 🌖CK电影部落－提供磁力／种子</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://blu-raydisc.tv/" target="_blank"> 🌗蓝光电影（名字是这个而已，非蓝光资源）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.youzhidy.com/" target="_blank"> 🌗优质电影网－提供下载直链</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.cilixiong.com/" target="_blank"> 🌗磁力熊－横幅色情广告－磁力</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.dygod.net/" target="_blank"> 🌗电影天堂（备用：dytt79.com／dy2018.com）－提供磁力</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://gaoqing.la/" target="_blank"> 🌗中国高清网（蓝光）－磁力</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.7meiju.com/" target="_blank"> 🌗七汉影视－百度云／磁力－需关注公众号</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.bd2020.com/" target="_blank"> 🌘BD影视分享－大面积广告－ed2k／迅雷云盘</a></li>
            </ul></li>
            <li><i class="fa fa-folder fa-lg"></i><a> 05.网页　仅电视剧（在线／下载）</a>
            <ul class="menu">
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.hanfan.cc/" target="_blank"> 🌕韩饭网－无广告－提供百度云🐢</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://ywtrzm.com/" target="_blank"> 🌖亿万同人字幕组－提供UC／115／百度云－免费注册后可在线</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.meijutt.tv/" target="_blank"> 🌘美剧天堂－大面积广告－提供磁力／百度云</a></li>
            </ul></li>
            <li><i class="fa fa-folder fa-lg"></i><a> 06.网页　仅电视剧（仅在线）</a>
            <ul class="menu">
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://mp.weixin.qq.com/s/Fhr0ji-izW7VNWGh3p2-1w" target="_blank"> 👍针对这类网站广告的解决方案：全平台网页去广告规则+使用教程</a></li>
                <li id="split" style="color:black;font-size:12px;opacity:0.7;">————————</li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.wwmulu.com/" target="_blank"> 🌕91日剧－无广告</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.novipnoad.com/" target="_blank"> 🌖NO视频（港台／日／欧美／土耳其／韩／泰剧）－无广告但很多资源目前失效了－支持IDM下载</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.jjhanju.com/frim/list1.html" target="_blank"> 🌕九九韩剧－无广告－支持IDM整段下载</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.zxzj.fun/" target="_blank"> 🌖在线之家（美／韩／日／泰）－横幅赌博广告</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://ddrk.me/" target="_blank"> 🌗低端影视（日韩／华语／欧美／其他）－横幅赌博广告</a></li>
                <li id="split" style="color:black;font-size:12px;opacity:0.7;">————————</li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.tvbs.cc/" target="_blank"> 🌗八零九零港剧网－PC端无广告／手机端大幅色情广告</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.yayameiju.com/" target="_blank"> 🌘爱美剧－PC端右下角弹窗广告／手机端底部色情广告</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.meijubs.com/" target="_blank"> 🌘美剧巴士－PC端右下角弹窗广告／手机端底部色情广告</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.bkmeiju.com/" target="_blank"> 🌘不卡美剧－PC端右下角弹窗广告／手机端底部色情广告</a></li>
            </ul></li>
            <li><i class="fa fa-folder fa-lg"></i><a> 07.网页　仅电视剧（仅下载）</a>
            <ul class="menu">
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.tnhsub.com/" target="_blank"> 东京不够热（日剧）－提供百度云／115🆕</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.ii166.com/" target="_blank"> 港剧下载（磁力）－顶部有广告</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.nnmeiju.com/" target="_blank"> 牛牛美剧 （蓝光）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://v.dsb.ink/#/" target="_blank"> SOZMZ－提供人人影视往日的所有影片信息及资源</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://yyets.dmesg.app/home" target="_blank"> 人人影视下载分享（人人凉凉之前有人爬了全站资源进而做的网站）👍</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://axu.lanzoui.com/i0tMRvy8dvc" target="_blank"> 人人影视全站17517部作品资源（内含被隐藏的磁力／ed2k／网盘链接）.xlsx🔥</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.chapianyuan.com/" target="_blank"> 查片源－磁力</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://gaoqing.fm/" target="_blank"> 高清电台－磁力</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://newzmz.com/index.html" target="_blank"> NEW字幕组－磁力／阿里云盘／百度云🐢</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.icezmz.com/" target="_blank"> 冰冰字幕组（未适配移动端）－阿里云／百度云</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://subs.kamigami.org/category/drama" target="_blank"> 诸神字幕组（日剧）－种子／百度云</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.zimuxia.cn/%e6%88%91%e4%bb%ac%e7%9a%84%e4%bd%9c%e5%93%81" target="_blank"> FIX字幕侠－提供阿里云／115／百度云／磁力／ed2k</a></li>
            </ul></li>
            <li><i class="fa fa-folder fa-lg"></i><a> 08.网页　动漫（在线／下载）</a>
            <ul class="menu">
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://mp.weixin.qq.com/s/Fhr0ji-izW7VNWGh3p2-1w" target="_blank"> 👍针对这类网站广告的解决方案：全平台网页去广告规则+使用教程</a></li>
                <li id="split" style="color:black;font-size:12px;opacity:0.7;">————————</li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.xbdm.org/" target="_blank"> 🌕迅播动漫－无广告</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://halihali3.com/" target="_blank"> 🌕哈哩哈哩（备用域名：halihali2.com／halihali.icu）－无广告</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.silisili.in/" target="_blank"> 🌖嘶哩嘶哩（也可看电视剧）－横幅广告</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://msiv.tv/" target="_blank"> 🌖弥生寺（免费注册后可观看）－无广告－支持IDM下载</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.agefans.cc/" target="_blank"> 🌖AGE动漫（备用：agefans.vip）－横幅二次元色情广告🐢</a></li>
                <li id="split" style="color:black;font-size:12px;opacity:0.7;">————————</li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.nicotv.biz/" target="_blank"> 🌘妮可动漫（备用：nicotv.club）－大幅广告</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.sbdm.net/" target="_blank"> 🌘异世界动漫（永久地址：tsdm.vip／天使动漫论坛：tsdm39.net）－大幅广告🆕</a></li>
            </ul></li>
            <li><i class="fa fa-folder fa-lg"></i><a> 09.网页　动漫（仅在线）</a>
            <ul class="menu">
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://mp.weixin.qq.com/s/Fhr0ji-izW7VNWGh3p2-1w" target="_blank"> 👍针对这类网站广告的解决方案：全平台网页去广告规则+使用教程</a></li>
                <li id="split" style="color:black;font-size:12px;opacity:0.7;">————————</li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.12wo.com/" target="_blank"> 🌕12WO动漫－无广告</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://dilidili.online/" target="_blank"> 🌕嘀哩嘀哩－无广告</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.qimiqimi.co/" target="_blank"> 🌕奇米奇米（永久域名：qimiqimi.com）－无广告🆕</a></li>
                <li id="split" style="color:black;font-size:12px;opacity:0.7;">————————</li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.milimili.tv/" target="_blank"> 🌖咪哩咪哩－横幅广告🐢</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.nieta.co/" target="_blank"> 🌖捏它追剧－横幅广告</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://anime1.me/" target="_blank"> 🌖Anime1.me 動畫線上看－二次元广告</a></li>
                <li id="split" style="color:black;font-size:12px;opacity:0.7;">————————</li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.ktkkt.top/" target="_blank"> 🌗卡通站（提供粤语版）－PC端无广告／手机端底部色情广告－🆕</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://tucao.one/" target="_blank"> 🌗吐槽弹幕网－大量横幅广告／未适配移动端</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.fengchedm.com/" target="_blank"> 🌗风车动漫－PC端右下角弹窗广告／手机端底部横幅广告</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.bimiacg4.net/" target="_blank"> 🌗哔咪动漫－大面积广告（域名发布页：bimiacg.one）🆕</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.imomoe.live/" target="_blank"> 🌘樱花动漫（邮箱：m20208888@hotmail.com）－底部大面积广告－超10年以上站点</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.yinghuacd.com/" target="_blank"> 🌘樱花动漫（邮箱：yhdmtv@outlook.com）－大面积广告</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.995dm.com/" target="_blank"> 🌘久久动漫（永久地址：dm55.cc）－大面积广告</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.dmdm2020.com/" target="_blank"> 🌘哆咪动漫－大面积广告</a></li>
            </ul></li>
            <li><i class="fa fa-folder fa-lg"></i><a> 10.网页　动漫（仅下载）</a>
            <ul class="menu">
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.dongman.fm/" target="_blank"> 动漫FM－百度云</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://acg.rip/" target="_blank"> ACG.RIP</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.36dm.com/" target="_blank"> 简单动漫（备用域名：36dm.club）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.comicat.org/" target="_blank"> 猫漫动漫BT下载</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.dmguo.org/forum.php" target="_blank"> 动漫国字幕组</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.dongmanhuayuan.com/" target="_blank"> 动漫花园资源网</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://dongmanhuayuan.myheartsite.com/" target="_blank"> 动漫花园同步站</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://mikanani.me/" target="_blank"> 蜜柑计划</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://bangumi.moe/" target="_blank"> 萌番组</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.kisssub.org/" target="_blank"> 爱恋动漫</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.miobt.com/" target="_blank"> MioBT</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://share.acgnx.se/" target="_blank"> 末日动漫资源库🚫</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.dmhy.org/" target="_blank"> 动漫花园🚫</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://share.dmhy.org/" target="_blank"> 动漫花园🚫</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://nyaa.si/" target="_blank"> Nyaa🚫</a></li>
            </ul></li>
            <li><i class="fa fa-folder fa-lg"></i><a> 11.ＴＶ　ＶIP影视／直播 📺</a>
            <ul class="menu">
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://axu.lanzouj.com/iWYpkz8o96h" target="_blank"> 📺　米奇TV 1.0永久破解版（1月25日测试可用／可看斗鱼虎牙B站）👍</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://axu.lanzouo.com/ihi7Bxcnqcb" target="_blank"> 📺　星火直播海外版1.0.06去购物台版（1月13日测试可用／可看港澳台）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://txt.fyi/-/2212/769661a3/" target="_blank"> 📺　火星直播 v1.8.5 无广告版（1月13日测试可用／可看港澳台）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://txt.fyi/-/2212/796098e6/" target="_blank"> 👑📺猫影视TV 2.0.8纯净版（1月13日测试可用）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://axu.lanzoui.com/iZvsUw7rupg" target="_blank"> 👑📺饭团影院TV 1.31 免登录（1月13日测试可用）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://axu.lanzouj.com/iz7VSyqqjmh" target="_blank"> 📺　海魂TV 3.0高级版⚠️勿更新（1月13日测试可用）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://zxmov.lanzouo.com/b0f91lb9c" target="_blank"> 👑　极光影视TV－源自公众号：极光终点站（1月13日测试可用）密码：92ld</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.fengcaizb.com/" target="_blank"> 📺　高清电视（1月13日测试可用）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://axu.lanzoui.com/i3Kw5w7r64b" target="_blank"> 📺　HDP直播 3.5.7 去广告版（1月13日测试可用）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.yuque.com/docs/share/706ff12a-da3a-42bd-91e4-7357f85ab892" target="_blank"> 👑📺老虎视频TV_2.0827纯净版（11月6日测试可用）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.znds.com/jc/" target="_blank"> ✅　由于电视机型号太多，安装教程各不相同，可以参照此链接（当贝市场提供的安装教程）</a></li>
            </ul></li>
            <li><i class="fa fa-folder fa-lg"></i><a> 13.电脑　ＶIP影视／直播 💻</a>
            <ul class="menu">
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://zyplayer.fun/" target="_blank"> 两端　ZY Player👍</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.lanzoui.com/u/GoldRiver" target="_blank"> WIN　海阔视界</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://jianpian.app/" target="_blank"> WIN　荐片播放器</a></li>
            </ul></li>
            <li><i class="fa fa-folder fa-lg"></i><a> 13.安卓　ＶIP影视／直播 📱</a>
            <ul class="menu">
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://axu.lanzouj.com/iPaODyqq2yh" target="_blank"> 青娃视频 1.7.8去广告纯净版（1月13日测试可用）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://axu.lanzouj.com/i7I3my14icj" target="_blank"> 小恋恋影视 6.2 VIP纯净版（12月27日测试可用）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://axu.lanzouj.com/iLHAAy158gj" target="_blank"> 酷享影视 1.1.0 去广告版（12月27日测试可用）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://axu.lanzouj.com/i02OXy15koj" target="_blank"> 杨桃影视 1.0.6 去广告版（12月27日测试可用）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://axu.lanzouj.com/i2R6Yy14h8j" target="_blank"> 麻瓜视频 8.8.8 纯净版（12月27日测试可用）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://axu.lanzouj.com/iqSRqy14tqj" target="_blank"> 好猫影视 1.0.5 破解版（12月27日测试可用）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://axu.lanzouj.com/iIrVfy159nc" target="_blank"> 百淘影视 1.1.6 纯净版（12月27日测试可用）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://txt.fyi/-/21360/1104b0a3/" target="_blank"> 海阔视界👍</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.yuque.com/docs/share/b5f50e05-56a1-4794-a1df-f325c7eb8ba5" target="_blank"> 点点新影视 9.3.9（12月27日测试可用）</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.lanzoui.com/b04s6a3re" target="_blank"> ZY Player 提取码：95px</a></li>
                <li id="split" style="color:black;font-size:12px;opacity:0.7;">————————</li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://app.zzzfun.com/" target="_blank"> ZzzFun－专看动漫</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://axu.lanzouj.com/iydXmy14i7e" target="_blank"> 森之屋 1.8.9－专看动漫（12月27日测试可用</a></li>
                <li id="split" style="color:black;font-size:12px;opacity:0.7;">————————</li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.yuque.com/docs/share/942cfb95-1331-4f10-b382-ee34fb4b6da2" target="_blank"> IPTV_Pro_v6.1.11（直播／可看港澳台）</a></li>
            </ul></li>
            <li><i class="fa fa-folder fa-lg"></i><a> 14.IＯS　ＶIP影视 📱</a>
            <ul class="menu">
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://dd88.app/" target="_blank"> 迪迪影院－AppStore版／1月18日测试：目前无任何广告👍</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://txt.fyi/-/21113/2f05b093/" target="_blank"> Launcher－AppStore版／11月6日测试：有启屏广告+APP内横幅广告</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://apps.apple.com/cn/app/id1570012860" target="_blank"> 看吧影视－AppStore版／11月6日测试：看1次广告免费看几个小时</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://apps.apple.com/cn/app/id1533237016" target="_blank"> 青蛙视频－AppStore版／11月6日测试：看1次广告免费看几个小时</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://www.panpan.la/index.html?ufacility=pc" target="_blank"> 盼盼影视－AppStore版做了伪装／11月6日测试：看1次广告免费看6小时</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://apps.apple.com/cn/app/id1590109163" target="_blank"> 人人旅游影视－AppStore版／11月6日测试：看1次广告免费看3小时</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://apps.apple.com/cn/app/id1550930782" target="_blank"> 曲奇影视－AppStore版做了伪装／11月6日测试：有启屏+视频开头广告</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://apps.apple.com/cn/app/id1585602857" target="_blank"> 云凯影视－AppStore版做了伪装／11月6日测试：看1次广告免费看3个小时</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://haomao.app/" target="_blank"> 好猫影视－AppStore版做了伪装／11月6日测试：有视频开头广告5秒后可跳过</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="https://apps.apple.com/cn/app/id1583904088" target="_blank"> 折尔影视－AppStore版／11月6日测试：看1次广告免费看3个小时</a></li>
                <li><i class="fa fa-internet-explorer "></i><a HREF="http://www.yunsheng.online/" target="_blank"> 美兰影视－AppStore版／11月6日测试：看1次广告免费看3个小时</a></li>
     

