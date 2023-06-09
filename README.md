
解析器规则：打开Quantumult X 配置文件，找到 [general] 位置，添加以下代码：

resource_parser_url=resource_parser_url=https://raw.githubusercontent.com/mgxray/Quantumult_x/main/Scripts/resource-parser.js

策略分组：打开Quantumult X 配置文件，找到 [policy] 位置，添加以下代码：

static=YouTube, server-tag-regex=HK|香港|🇭🇰|TW|台湾|🇹🇼|US|美国|🇺🇸, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/YouTube.png
static=Netflix, server-tag-regex=流媒体|解锁|原生|家宽|Netflix|netflix|HBO|劫持解锁|原生解锁|NF|hulu|Hulu|HBO|hbo|Spotify|spotify|Disney+|disney+|Disney|disney, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Netflix.png
static=Disney+, server-tag-regex=流媒体|解锁|原生|家宽|Netflix|netflix|HBO|劫持解锁|原生解锁|NF|hulu|Hulu|HBO|hbo|Spotify|spotify|Disney+|disney+|Disney|disney, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Disney+.png
static=HBO, server-tag-regex=流媒体|解锁|原生|家宽|Netflix|netflix|HBO|劫持解锁|原生解锁|NF|hulu|Hulu|HBO|hbo|Spotify|spotify|Disney+|disney+|Disney|disney, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/HBO.png
static=Hulu, server-tag-regex=流媒体|解锁|原生|家宽|Netflix|netflix|HBO|劫持解锁|原生解锁|NF|hulu|Hulu|HBO|hbo|Spotify|spotify|Disney+|disney+|Disney|disney, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Hulu.png
static=Spotify, server-tag-regex=流媒体|解锁|原生|家宽|Netflix|netflix|HBO|香港|🇭🇰|台湾|🇹🇼|HK|TW, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Spotify.png
static=TikTok, server-tag-regex=US|美国|🇺🇸|TikTok|UK|英国|🇬🇧|日本|🇯🇵|台湾|🇹🇼|JP|TW|tiktok, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/TikTok.png
static=Telegram, server-tag-regex=香港|🇭🇰|HK|台湾|🇹🇼|TW|新加坡|🇸🇬|SG|狮城, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Telegram.png
static=Twitter, server-tag-regex=US|美国|🇺🇸, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Twitter.png
static=Facebook, server-tag-regex=US|美国|🇺🇸|香港|🇭🇰|HK|台湾|🇹🇼|TW, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Facebook.png
static=Instagram, server-tag-regex=US|美国|🇺🇸|香港|🇭🇰|HK|台湾|🇹🇼|TW|日本|🇯🇵|JP, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Instagram.png
url-latency-benchmark=国际网络（自动选择节点）, server-tag-regex=.*, check-interval=600, tolerance=0, alive-checking=false, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/World_Map.png

分流规则：打开Quantumult X 配置文件，找到 [filter_local] 位置，添加以下代码：

host-keyword, instagram, Instagram
host-keyword, hulu, Hulu
host-keyword, netflix, Netflix
host-keyword, facebook, Facebook
host-keyword, disney, Disney+
host-keyword, hbo, HBO
host-keyword, youtube, YouTube
host-keyword, tiktok, TikTok
host-keyword, netflix, Netflix
host-keyword, spotify, Spotify
host-keyword, telegram, Telegram

解锁Spotify规则：打开设置---重写===规则资源----填写下面规则

https://raw.githubusercontent.com/erdongchanyo/Rules/main/Quantumult%20X/AllinOneRewrite/edc.conf
