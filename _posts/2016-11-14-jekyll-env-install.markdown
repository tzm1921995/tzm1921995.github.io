---
title:  "jekyll env on ubuntu"
date:   2016-11-14 11:04:23
categories: [tools]
tags: [tools]
---
#### github page 
ubuntu下安装相关环境
[ruby](https://www.ruby-lang.org/en/downloads/)
下载ruby-2.3.1.tar.gz

```
# sudo apt-get install software-properties-common
# sudo apt-add-repository ppa:brightbox/ruby-ng
# sudo apt-get update
# sudo apt-get install ruby2.3 ruby2.3-dev
# gem install rubygems-update
```

[nodejs](https://nodejs.org/en/) 

```
tar xf node-v6.9.1-linux-x64.tar.xz
mv node-v6.9.1-linux-x64 /usr/local/node
ln -s /usr/local/node/bin/node /usr/bin/node
ln -s /usr/local/node/bin/npm /usr/bin/npm
```

[jekyll](https://jekyllrb.com/docs/installation/)

```
gem install jekyll
```
运行jekyll

```
jekyll server -H 0.0.0.0 -P 80 --watch --drafts
```
打开 http://SERVER_IP 预览


<table>
<!-- 来必力City版安装代码 -->
<div id="lv-container" data-id="city" data-uid="MTAyMC8zOTMxMi8xNTgzOQ==">
	<script type="text/javascript">
   (function(d, s) {
       var j, e = d.getElementsByTagName(s)[0];

       if (typeof LivereTower === 'function') { return; }

       j = d.createElement(s);
       j.src = 'https://cdn-city.livere.com/js/embed.dist.js';
       j.async = true;

       e.parentNode.insertBefore(j, e);
   })(document, 'script');
	</script>
<noscript> 为正常使用来必力评论功能请激活JavaScript</noscript>
</div>
<!-- City版安装代码已完成 -->
</table>
