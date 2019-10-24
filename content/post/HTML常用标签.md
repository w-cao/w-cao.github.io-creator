---
title: "HTML常用标签"
date: 2019-10-23T18:36:44+08:00
draft: false
---
 
# a 标签

## a 标签的属性和作用

* 属性

1. href
2. target
3. download
4. rel=noopener

*  作用
1. 跳转外部页面
2. 跳转内部锚点
3. 跳转到邮箱或电话等

## a的href的取值

*  网址
1. https://google.com
2. http://google.com
3. //google.com
   
*  路径
1. /a/b/c 以及 a/b/c
2. index.html 以及 ./index.html

*  伪协议
1. javascript:代码;
2. mailto:邮箱
3. tel:手机号
   
*  id
- [x] href=#xxx

## a的target的取值

*  内置名字
1. _blank
2. _top
3. _parent
4. _self

*  程序远命名
1. window的name
2. iframe的name
   
## a的download

* 作用
- [x] 不是打开页面, 而是下载页面

* 问题
- [x] 不是所有浏览器都支持, 尤其是手机浏览器可能不支持

# table 标签

*  相关的标签
1. table
2. thead
3. tbody
4. tfoot
5. tr
6. td
7. th

*  相关的样式
1. table-layout
2. border-collapse
3. border-spacing

#  img 标签

 
* 作用
- [x] 发出get请求, 展示一张图片
* 属性
- [x] alt/height/width/src
* 事件
- [x] onload/onerror
* 响应式
- [x] max-width:100%
* [可替换的元素](https://developer.mozilla.org/zh-CN/docs/Web/CSS/Replaced_element) 

#  form 标签
 

*  作用
- [x] 发get或post请求, 然后刷新页面
*  [属性](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/form) 
*  事件
- [x] onsubmit

# input 标签

* 作用
- [x] 让用户输入内容
* 属性
- [x] 类型type: button/checkbox/email/file/hidden
/number/password/radio/search/submit/tel/text
- [x] 其他name/autofocus/checked/disabled/maxlength/pattern/value/placeholder
* 事件
- [x] onchange/onfocus/onblur
* 验证器
- [x] HTML5新增功能

# 其他输入标签

*  标签
1. select + option
2. textarea
3. label
   
*  注意事项
1. 一般不监听input的click事件
2. form里面的input要有name
3. form里面放一个type=submit才能触发submit事件

# 其他标签

*  标签
1. video
2. audio
3. canvas
4. svg


# 开发规范(感想)

* 使用server调试html代码

1. yarn global add parcel 运行 parcel demo.html
2. yarn global add http-server 运行 hs -c-1








