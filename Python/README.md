##爬取脚本##
这是爬取拉钩网,指定职位(Hadoop,Spark,数据挖掘,数据分析)信息的脚本

###使用注意###
- 默认存储爬取来的内容的文件夹为/home/hadoop/crawlerData/当天日期/职位名称_hb.txt
- 请将加载数据到HBase中的Jar放置到/home/hadoop/runJar/下
- 爬虫日志保存地址为/home/hadoop/pythonTest/ 保存文件名为myCrawler.log,可自行修改配置文件指定存储位置及名称
- 请使用Python 3运行本脚本
- 请保持网络畅通

##更新历史##
###版本:1.0 更新时间 2015-12-26###