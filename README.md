本幻灯片由[R](http://www.r-project.org) + [slidify](http://slidify.org)编译

## 准备工作

在R中需要先安装slidify包

```
library(devtools)
install_github('slidify', 'ramnathv')
```
## 编译

然后编译index.Rmd文件

```
library(slidify)
slidify("index.Rmd")
```

## 阅读幻灯片

有两种方式阅读幻灯片

- 本地查看，打开index.html就可以查看，需要联网
- 将编译出来的文件push到github上代码库的gh-pages分支就可以，比如[在线查看本幻灯片](http://yanping.me/github-pages-tutorial)

