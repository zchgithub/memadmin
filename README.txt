```
From :http://www.junopen.com/memadmin/
MemAdmin是一款可视化的Memcached管理与监控工具，使用PHP开发，体积小，操作简单。

主要功能：

服务器参数监控：STATS、SETTINGS、ITEMS、SLABS、SIZES实时刷新
服务器性能监控：GET、DELETE、INCR、DECR、CAS等常用操作命中率实时监控
支持数据遍历，方便对存储内容进行监视
支持条件查询，筛选出满足条件的KEY或VALUE
数组、JSON等序列化字符反序列显示
兼容memcache协议的其他服务，如Tokyo Tyrant (遍历功能除外)
支持服务器连接池，多服务器管理切换方便简洁
```


MemAdmin v 1.0.11
 
 2012/6/6

 Installation :

 1. Download MemAdmin from http://www.junopen.com/memadmin
 2. Unzip the files into your web root
 3. Set your username and password in the config.php
 4. Visit the index.php in your browser : http://example.com/memadmin/index.php


 BUGs Report : junstor@gmail.com

 Changelog :
 v1.0.12 -- 2012/8/15
   * fix a refer bux

 v1.0.11 -- 2012/6/6
   * fix expire time bug

 v1.0.10 -- 2012/4/17
   * fix a bug when session.auto_start=1
   
 v1.0.9 -- 2012/2/4
   * fix five bugs
   * Add charset support
   * Add touch command support
   * Compatible with memcached v1.4.11/v1.4.12/v1.4.13

 v1.0.8 -- 2011/11/9
   * fix two bugs

 v1.0.7 -- 2011/11/8
   * fix one bug
 
 v1.0.6 -- 2011/10/9
   * fix two bugs
   
 v1.0.5 -- 2011/8/24
   * Add Refresh Button
   
 v1.0.4 -- 2011/8/21
   * Htmlspecialchars for Key & Value
 
 v1.0.3 -- 2011/8/20  
   * Compatible with memcached v1.4.7
   * Add English support
   
 v1.0.2 -- 2011/8/18
   * Add stripslashes in GetList.php
   * The regular expression demo div fit the body width
   
 v1.0.1 -- 2011/8/10
   * Basic Version
