title: win10 系统 chrome内核浏览器 微软雅黑字体难看的解决方法
date: 2015-10-14 10:30:55 +0800
update: 2015-10-14 10:30:55 +0800
author: fungleo
tags:
    -chrome
    -微软雅黑字体
    -字体难看解决方法
---

升级到win10之后，我对win10的感觉还是很好的。但是，我总感觉win10的微软雅黑字体发生了改变，变得异常难看，尤其是在加粗的情况下。这让我很是不爽，但又没有任何办法。

偶然情况下，我将网页切换到了IE核心，发现字体瞬间变得好看了。我顿时想到这不是win10的问题，而是chrome内核的问题。迅速百度，终于找到了解决方法。原来是打开了 DirectWrite 这个选项的问题。

我用的是搜狗浏览器。`ctrl+shift+s`，打开`设置`页面，点击导航中的`高级`，往下拖动，`实验室，更多高级设置`在里面关掉 DirectWrite 即可。

chrome 原生浏览器，在地址栏输入` chrome://flags/` 即可开启关闭 DirectWrite 选项了。

QQ浏览器，在地址栏输入` qqbrowser://flags/` 这个我没有验证。

其他浏览器可以根据这个思路来解决问题。

--------------------

资料参考网址：http://bbs.pcbeta.com/viewthread-1618905-1-1.html
