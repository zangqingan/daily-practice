# quality-purchase(品优购)
    黑马pink老师的PC端静态电商项目
## 1. 网址图标favicon.ico
    在原型上切图然后去在线网址转化即可，也可以直接在线制作。给浏览器用的放在根目录。
    http://bitbug.net/，比特虫。
    引入：<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
## 2. 网站优化(SEO)
    SEO(search engine optimization)搜索引擎优化，利于别人通过搜索引擎查找到你的网址
* 网页title标签
    建议：网址(产品)名+核心功能特点介绍
    <!-- <title>品优购-综合网购首选-品质保证,价格优惠</title> -->
* meta元信息里的description属性
    对网址进行说明，即一个主体概括。
    <!-- <meta name="description" content="品优购-专业综合网上购物商城，销售超数万品牌，4020万种商品，囊括家电、手机、电脑、服装、居家、母婴、美妆、个护、食品、旅游等13大品类。京东PLUS会员，免费体验30天！京东秉承客户为先，
     100％正品行货保障，提供全国联保，机打发票，专业配送，售后服务！"> -->
* keywords关键字
    描述网页的关键词，搜索引擎关注的点，一般6到8个即可。
    <!-- <meta name="keywords" content="家电、手机、电脑、服装、居家、母婴、美妆、个护、食品、旅游等"> -->
## 3. iconfont字体图标
    像图片但是能和字体一样设置大小颜色等。ui给的svg图片可以在线上转化为字体图标。
    阿里云矢量图标库：https://www.iconfont.cn/，
    icomoon：https://icomoon.io/
* 使用
    同一放到一个fonts文件夹里
## 4. 首页开始
对应替换行内元素是可以设置宽高的如 img，input，button

ps使用拉辅助线，选用矩形框选工具测算大小。

main首页主体部分内容
中间一个轮播图，右边一个新闻列表newList


## 5. 学习体会
写样式是没有什么大的技术上的难度，就是怎么在网页上摆放矩形盒子的过程，多写多练多看多模仿。
同时写样式也是很枯燥繁琐重复的，一定要沉得住气。
在浮动和定位的布局里，一定要注意浮动带来的影响及解决方案。
在自己布局时想不到就用div+css没毛病，对于少量的字需要设置特殊的样式时可以使用 span， i，em，strong这几个行内标签。浏览器渲染的和自己写的有出入记得打开调试工具查看并分析原因