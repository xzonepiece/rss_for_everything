# rss_for_everything
在一个RSS阅读器中阅读所有信息源提供的内容，包括微信公众号、简书、知乎、博客、图虫、Lofter。。。

###1. 订阅源
####1.1. 订阅微信公众号
其实，订阅微信公众号是非常麻烦的，在这里**推荐使用[微广场](http://www.iwgc.cn/)**，它提供微信公众号的全文RSS，免费用户可以订阅10个公众号，而且基本上热门的公众号都能找到；然后[微口网](http://www.vccoo.com/)也不错，上面的公众号也比较多，不过，它只提供摘要RSS；之前还有好多类似的服务，可惜好像都已经失效了，比如，[狗耳朵](http://www.dogear.cn/)，[微合网](http://www.weiheji.net/)；还有一些聚合微信公众号的网站，比如[传送门](http://chuansong.me/)、[爱微帮](http://www.aiweibang.com/u/167)，它们只提供在它们自己网站上订阅，不支持订阅RSS；最后，推荐一个开源应用[RSS生成器](https://github.com/wlwr/rss)，可以自己部署到云端，支持微信公众号 RSS 订阅，作者基于[搜狗微信](http://weixin.sogou.com/)写的，也就是说，搜狗上能搜到的微信公众号，都能通过这种方式订阅。
####1.2. 订阅简书
至于简书，推荐一个网站[Jianshu RSS](http://jianshu.milkythinking.com/)，使用方法非常简单，直接将你想订阅的简书专题或作者主页的网站粘贴到输入框中，点击GO就可以生成对应的RSS源。

####1.3. 订阅知乎专栏
订阅知乎专栏可使用这个[网站](https://rss.lilydjwg.me/)提供的服务，但是，因为**知乎上的图片好像有图片防盗链设置**，为了让图片能够正确显示，浏览器上需要安装一些插件，比如：[RefControl](https://chrome.google.com/webstore/detail/referer-control/hnkcfpcejkafcihlgbojoidoihckciin?utm_campaign=en&utm_source=en-et-na-us-oc-webstrhm&utm_medium=et)，或[My Webrequest](http://app.evecalm.com/MyWebrequest/)，使用方法参见插件自身的教程。
####1.4. 订阅博客
大部分博客都是提供RSS订阅的，图虫、Lofter这类图片类轻博客也是支持的，但是如果网站不提供怎么办，在这里你可以使用[feed43](http://feed43.com/)，我在之前的[文章](http://www.jianshu.com/p/9bc3fedb1ca3)中也提到过，使用教程可以参见[小众软件](http://www.appinn.com/feed43/)，操作也比较简单。
####1.5. 订阅微博
如果你需要将微博上的一些账号变成RSS的话，可以试试[微博档案](http://weibo.wbdacdn.com/)。
####1.6. 订阅任意网站
如果你想将任意网站变成RSS的话，你可能需要自己去写代码啦，不过也有一些软件可以做到，在这里强烈推荐一款开源应用—[Huginn](https://github.com/cantino/huginn/wiki)，需要自己将代码部署到云端，喜欢折腾的人可以去试试，官方教程很详细。它的功能非常强大，不仅仅是能将任意网站变成RSS，还可以实现很多自定义功能，有点类似IFTTT。想尝鲜的人可以试试有人搭建好的Huginn网站，邀请码是*try-huginn*，烧制RSS的教程参见这篇文章—[Huginn: 烧录 RSS 的神器](http://www.jianshu.com/p/4a47e452abc9)。前面我提到微口网只提供摘要RSS，这样的话，你就可以使用Huginn将摘要RSS变成全文RSS，你也可以将传送门或爱微帮上的公众号变成RSS。
###2. RSS阅读器
下面介绍几个比较好的RSS阅读器：
####2.1. [Inoreader](www.inoreader.com)
这是我自己现在使用的RSS阅读器，它最突出的功能是**可以自动地将一些摘要RSS变成全文RSS（快捷键W）**，而且还**支持自定义订阅源规则**，强推，网页端有广告，但是，使用一些浏览器插件很容易就可以去广告的，而且，手机端上是没有广告的。
####2.2. [一览](http://www.yilan.io/home/)
之所有推荐这款RSS阅读器是因为它针对国人来说，实在是太接地气了，**自带微信公众号和知乎订阅**，阅读体验做得也很不错，还具有推送Kindle服务，要不是我已经习惯了Inoreader的话，我应该会首选使用它。免费版最多可以订阅100个RSS源、10个微信公众号。
除了上面这两个阅读器以外，还有很多优质的RSS阅读器，比如IOS上首推的Reeder、the old reader、feedly、深蓝阅读，等等。
###3. RSS相关工具
下面推荐一些RSS相关的工具：
[Huginn](https://github.com/cantino/huginn/wiki)：**神器**，不仅仅是制作RSS
[feed43](http://feed43.com/)：可以为静态网站制作RSS
[IFTTT](https://ifttt.com/)：可以将RSS与其他应用连接起来
[Reabble](http://reabble.com/)：通过该服务可以在kindle上阅读RSS
[feedburner](https://feedburner.google.com)：烧制RSS，可以用来管理自己制作的RSS
[fivefilters](http://fivefilters.org/content-only/)：可以将摘要RSS变成全文RSS
[即刻](http://www.ruguoapp.com/)：基于RSS理念的一款APP
[RSS Subscription Extension](https://chrome.google.com/webstore/detail/rss-subscription-extensio/nlbjncdgjeocebhnmkbbbdekmmmcbfjd)：chrome插件，为浏览器添加一键订阅RSS功能，自动发现网页上的RSS源

