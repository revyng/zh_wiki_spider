https://github.com/wjn1996/scrapy_for_zh_wiki 的改造版本

代理配置：
直接在运行 scrapy 的电脑本地开一个代理就行，然后运行项目，即可抓取 wiki 页面

Wiki 并没有设什么反爬，只要你的爬虫不太离谱（比如搞成 ddos 了），就能抓到数据，这个爬虫的主要工作量在数据处理、url 去重之类的设计。

