# so
搜easy,更快的定位到需要的信息关键字

## 解决的问题 ##

 - 平常工作经常grep关键词，出来的很多无用的内容，需要从这些再次筛选
 - grep 需要带很多不同的参数
 - 针对widget、php、js、less我所经常的遇到的grep的方式做了一些快捷的方式
 - 排除 *svn, output, build文件夹下的文件

## 安装 ##
 - 在你的ocean上，cd ~/bin 
 - scp zhangshibiao@cp01-rdqa-dev144.cp01.baidu.com:~/bin/so ~/bin/
 - 或者down之后把so放在~/bin下

 ## 使用 ##

	demo 搜索  vertical_head

```
so -h  提示信息
so vertical_head -w   搜索     $__widget__->loa(vertical_head)
so vertical_head -p   在php文件中搜索
so vertical_head -j   在js文件中搜索
so vertical_head -l   less
so vertical_head -c   css
so vertical_head      默认所有的
```
