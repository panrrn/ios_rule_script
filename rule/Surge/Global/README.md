# Global

## 前言

本项目的Global分流规则由爬虫程序自动维护。

定时爬取互联网上开源的Global分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。

Global分流规则中含有URL-REGEX类型，此类的规则对于HTTPS请求需要MITM使用才能生效。程序已默认根据正则推导一份MITM的模块/复写/插件在当前分流规则的目录中，便于参考搭配使用。

最后检查时间：2021-03-19 01:55:36.951799。

## 规则统计

总计规则：29178 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN-SUFFIX | 28916 |
| USER-AGENT | 49 |
| DOMAIN | 39 |
| DOMAIN-KEYWORD | 42 |
| IP-CIDR | 127 |
| IP-CIDR6 | 3 |
| PROCESS-NAME | 1 |
| URL-REGEX | 1 |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### Surge 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global.list

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Domain.list

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Surge/Global/Global.list

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Surge/Global/Global_Domain.list

如果稳定版无法访问 ，可能是尚未从实时版的分支合并，建议您先使用实时版，或等待下次稳定版分支合并。

### 特别说明

Global.list请使用RULE-SET。

Global_Domain.list请使用DOMAIN-SET。

## 重复统计

当前分流规则，已包含以下子规则：

- Proxy

除非特殊需求，否则不建议重复引用。


当前分流规则，与本项目其他分流规则重复情况统计(点击重复数量可查看明细)。



| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [9to5](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/9to5)    | 7   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [ATTWatchTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/ATTWatchTV)    | 6   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Atlassian](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Atlassian)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [CNN](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/CNN)    | 6   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Comodo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Comodo)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [DigiCert](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/DigiCert)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Espn](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Espn)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Jwplayer](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Jwplayer)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [KKBOX](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/KKBOX)    | 7   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Picsee](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Picsee)    | 6   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Reddit](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Reddit)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Sectigo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Sectigo)    | 7   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Shopify](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Shopify)    | 8   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Slack](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Slack)    | 8   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Sling](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Sling)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Snap](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Snap)    | 6   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Spark](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Spark)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Stackexchange](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Stackexchange)    | 15   | [15](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [VK](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/VK)    | 7   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Voxmedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Voxmedia)    | 16   | [16](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [WIX](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/WIX)    | 9   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Wikimedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Wikimedia)    | 20   | [20](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Wikipedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Wikipedia)    | 12   | [12](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Wordpress](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Wordpress)    | 8   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Zendesk](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Zendesk)    | 6   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Proxy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Proxy)    | 29098   | [29010](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   99.7% |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/BlackList)    | 772   | [760](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   98.45% |
|  [VOA](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/VOA)    | 51   | [49](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   96.08% |
|  [Developer](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Developer)    | 24   | [23](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   95.83% |
|  [DtDNS](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/DtDNS)    | 17   | [16](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   94.12% |
|  [Vimeo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Vimeo)    | 16   | [15](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   93.75% |
|  [Twitter](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Twitter)    | 26   | [24](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   92.31% |
|  [EA](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/EA)    | 163   | [150](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   92.02% |
|  [Adobe](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Adobe)    | 138   | [126](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   91.3% |
|  [Bloomberg](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Bloomberg)    | 22   | [20](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   90.91% |
|  [Line](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Line)    | 22   | [20](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   90.91% |
|  [Discord](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Discord)    | 10   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   90.0% |
|  [PayPal](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/PayPal)    | 248   | [222](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   89.52% |
|  [Dell](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Dell)    | 117   | [104](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   88.89% |
|  [Fox](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Fox)    | 257   | [228](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   88.72% |
|  [Dropbox](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Dropbox)    | 17   | [15](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   88.24% |
|  [HuluUSA](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/HuluUSA)    | 51   | [45](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   88.24% |
|  [DynDNS](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/DynDNS)    | 8   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   87.5% |
|  [KakaoTalk](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/KakaoTalk)    | 14   | [12](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   85.71% |
|  [Hulu](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Hulu)    | 56   | [47](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   83.93% |
|  [Riot](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Riot)    | 54   | [45](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   83.33% |
|  [Gucci](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Gucci)    | 6   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   83.33% |
|  [Github](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Github)    | 23   | [19](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   82.61% |
|  [Zee](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Zee)    | 22   | [18](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   81.82% |
|  [Xbox](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Xbox)    | 36   | [29](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   80.56% |
|  [Bestbuy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Bestbuy)    | 82   | [66](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   80.49% |
|  [Facebook](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Facebook)    | 68   | [54](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   79.41% |
|  [BrightCove](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/BrightCove)    | 14   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   78.57% |
|  [ZeeTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/ZeeTV)    | 9   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   77.78% |
|  [Cisco](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Cisco)    | 118   | [91](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   77.12% |
|  [AppleDaily](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AppleDaily)    | 13   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   76.92% |
|  [IBM](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/IBM)    | 13   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   76.92% |
|  [Samsung](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Samsung)    | 13   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   76.92% |
|  [Nintendo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Nintendo)    | 123   | [94](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   76.42% |
|  [Spotify](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Spotify)    | 21   | [16](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   76.19% |
|  [CBS](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/CBS)    | 30   | [22](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   73.33% |
|  [SmarTone](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/SmarTone)    | 15   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   73.33% |
|  [Vercel](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Vercel)    | 15   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   73.33% |
|  [PCCW](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/PCCW)    | 25   | [18](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   72.0% |
|  [Scholar](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Scholar)    | 177   | [127](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   71.75% |
|  [Zoho](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Zoho)    | 13   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   69.23% |
|  [NYTimes](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/NYTimes)    | 16   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   68.75% |
|  [Google](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Google)    | 111   | [76](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   68.47% |
|  [AbemaTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AbemaTV)    | 22   | [15](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   68.18% |
|  [Game](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Game)    | 533   | [356](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   66.79% |
|  [Logitech](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Logitech)    | 9   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   66.67% |
|  [Manorama](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Manorama)    | 12   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   66.67% |
|  [Mozilla](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Mozilla)    | 18   | [12](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   66.67% |
|  [Pixnet](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Pixnet)    | 9   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   66.67% |
|  [Whatsapp](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Whatsapp)    | 21   | [14](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   66.67% |
|  [Pinterest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Pinterest)    | 23   | [15](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   65.22% |
|  [Netflix](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Netflix)    | 43   | [28](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   65.12% |
|  [Nike](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Nike)    | 11   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   63.64% |
|  [Qualcomm](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Qualcomm)    | 44   | [28](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   63.64% |
|  [Telegram](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Telegram)    | 30   | [19](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   63.33% |
|  [Disney](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Disney)    | 132   | [83](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   62.88% |
|  [Amazon](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Amazon)    | 168   | [105](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   62.5% |
|  [LineTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/LineTV)    | 8   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   62.5% |
|  [Rarbg](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Rarbg)    | 16   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   62.5% |
|  [AmazonPrimeVideo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AmazonPrimeVideo)    | 26   | [16](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   61.54% |
|  [iCloud](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/iCloud)    | 51   | [31](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   60.78% |
|  [Niconico](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Niconico)    | 10   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   60.0% |
|  [Microsoft](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Microsoft)    | 471   | [281](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   59.66% |
|  [Duckduckgo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Duckduckgo)    | 43   | [25](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   58.14% |
|  [TikTok](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/TikTok)    | 16   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   56.25% |
|  [BBC](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/BBC)    | 22   | [12](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   54.55% |
|  [Shopee](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Shopee)    | 11   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   54.55% |
|  [HBOHK](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/HBOHK)    | 14   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   50.0% |
|  [Cloudflare](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Cloudflare)    | 41   | [20](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   48.78% |
|  [BMW](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/BMW)    | 729   | [354](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   48.56% |
|  [Naver](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Naver)    | 60   | [29](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   48.33% |
|  [Intel](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Intel)    | 263   | [126](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   47.91% |
|  [OneDrive](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/OneDrive)    | 19   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   47.37% |
|  [Dailymail](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Dailymail)    | 17   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   47.06% |
|  [Oracle](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Oracle)    | 25   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   44.0% |
|  [HBO](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/HBO)    | 32   | [14](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   43.75% |
|  [TVB](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/TVB)    | 21   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   42.86% |
|  [DAZN](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/DAZN)    | 19   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   42.11% |
|  [Garena](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Garena)    | 15   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   40.0% |
|  [Verizon](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Verizon)    | 182   | [71](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   39.01% |
|  [Globalsign](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Globalsign)    | 13   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   38.46% |
|  [Apple](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Apple)    | 116   | [44](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   37.93% |
|  [Sony](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Sony)    | 116   | [43](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   37.07% |
|  [Verisign](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Verisign)    | 33   | [12](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   36.36% |
|  [Huffpost](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Huffpost)    | 18   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   33.33% |
|  [Twitch](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Twitch)    | 18   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   33.33% |
|  [YouTube](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/YouTube)    | 180   | [60](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   33.33% |
|  [ThomsonReuters](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/ThomsonReuters)    | 31   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   32.26% |
|  [eBay](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/eBay)    | 44   | [14](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   31.82% |
|  [Canon](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Canon)    | 70   | [22](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   31.43% |
|  [AppleProxy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AppleProxy)    | 16   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   31.25% |
|  [Westerndigital](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Westerndigital)    | 23   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   30.43% |
|  [Starbucks](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Starbucks)    | 32   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   28.12% |
|  [McDonalds](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/McDonalds)    | 26   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   26.92% |
|  [Gettyimages](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Gettyimages)    | 25   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   24.0% |
|  [Blizzard](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Blizzard)    | 61   | [14](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   22.95% |
|  [VISA](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/VISA)    | 99   | [21](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   21.21% |
### 特别说明
程序在实际运算时，会根据DOMAIN、DOMAIN-SUFFIX、IP-CIDR、IP-CIDR6间的包含关系进行去重，而出于运行效率考虑，重复规则只统计纯文本匹配，所以可能与实际效果有所出入，仅供参考。

## 数据来源

本项目的Global分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，建议不要与本项目的Global分流规则混合使用，以免造成规则重复。

- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyGFWlist.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyLite.list
- https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Ruleset/Global.list
- https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Ruleset/GlobalMedia.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Global.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Global.list
- https://raw.githubusercontent.com/GeQ1an/Rules/master/QuantumultX/Filter/Outside.list
- https://raw.githubusercontent.com/Hackl0us/SS-Rule-Snippet/master/Rulesets/Surge/Basic/Apple-proxy.list
- https://raw.githubusercontent.com/Loyalsoldier/surge-rules/release/ruleset/gfw.txt
- https://raw.githubusercontent.com/Loyalsoldier/surge-rules/release/ruleset/greatfire.txt
- https://raw.githubusercontent.com/Loyalsoldier/surge-rules/release/ruleset/proxy.txt
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/BlackList/BlackList.list
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/Proxy/Proxy.list
- https://raw.githubusercontent.com/eHpo1/Rules/master/Surge4/Ruleset/Global.list
- https://raw.githubusercontent.com/lhie1/Rules/master/Surge/Surge%203/Provider/Proxy.list
- https://raw.githubusercontent.com/sve1r/Rules-For-Quantumult-X/develop/Rules/Region/Global.list


感谢以上分流规则作者的辛勤付出（排名不分先后）。

如果您有更好的分流规则，欢迎提交给我，我会将它加到数据源中继续完善。

## 程序特点

### 断链处理

对于某些已删除或失效的数据源，继续使用本地缓存的文件，减少因为断链造成的影响。

### 规则过滤

通过关键字、正则、模糊匹配三种方式对规则进行过滤，以移除部分数据源中的错误规则。

### 合并去重

不仅对完全相同的规则进行去重，还会根据DOMAIN、DOMAIN-SUFFIX、IP-CIDR、IP-CIDR6等规则间的包含关系进行合并去重。

### 域名解析

对DOMAIN类型的规则进行DNS解析记录查询，丢弃连续多次无法解析的域名。

### 正则合并

通过程序对相似正则进行合并，不定时手动核验正则合并结果。

### 正则推导

通过程序对含有正则的规则，推导需要MITM的主机名，不定时手动核验推导结果。

### 正则编译

通过程序对正则类型的规则进行编译，去除无法通过编译的正则。

## 最后

### 完善规则

如果您：

1. 有更优的原始规则数据
2. 有更多的黑名单规则数据
3. 有更好的优化建议
4. 在使用分流规则时出现异常
5. 有其他问题

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的Global分流规则。

感谢

[@fiiir](https://github.com/fiiir) [@Tartarus2014](https://github.com/Tartarus2014) [@zjcfynn](https://github.com/zjcfynn) [@chenyiping1995](https://github.com/chenyiping1995) 

提供规则数据源及改进建议

### 其他问题

爬虫开发的初衷是为满足自己几方面需求：

1. 去除混用多个去广告规则造成的重复
2. 去除多个去广告规则中某些规则
3. 多个分流规则间重复情况检查
4. 定时同步数据源更新

本项目的分流规则还是以自用为主，请不要对外宣传此分流规则。所以，还是请低调使用吧。