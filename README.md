# web-xiu 工具函数

> good good study, day day up！
![](https://images.pexels.com/photos/2653362/pexels-photo-2653362.jpeg?auto=compress&cs=tinysrgb&dpr=3&h=750&w=1260)<br>

## 效果预览

>
### 👉预览地址：[请点我！在线预览](https://www.npmjs.com)

![](https://images.pexels.com/photos/1634229/pexels-photo-1634229.jpeg?auto=compress&cs=tinysrgb&dpr=3&h=750&w=1260)<br>


### 工具类别

金额类验证 + 用户信息验证 + 邮箱联系方式验证 ...

### 工具描述

> * 金额类验证
> * 用户信息验证
> * 邮箱联系方式验证
> * 字符串处理
> * 数组结构
> * 对象解构
> * 循环

## 具体功能实现

#### 代码片段

``` javascript
 function html_encode(str) {
     var s = '';
     if (str.length == 0) return "";
     s = str.replace(/&/g, "&amp;");
     s = s.replace(/</g, "&lt;");
     s = s.replace(/>/g, "&gt;");
     s = s.replace(/\s/g, "&nbsp;");
     s = s.replace(/\'/g, "&#39;");
     s = s.replace(/\"/g, "&quot;");
     s = s.replace(/\n/g, "<br/>");
     return s;
 }
```


## Install

``` bash
# install dependencies
npm i web-xiu --save

# use dependencies
let webXiu = require("web-xiu")
webxiu.formatDouble(30,2)


```

For detailed explanation on how things work, checkout the [contact me](http://www.lixiuhai.com) and [docs for vue](https://cn.vuejs.org/) ,[docs for ES6](http://es6.ruanyifeng.com/).

