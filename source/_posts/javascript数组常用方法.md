---
title: javascript数组常用方法
date: 2022-09-14 09:56:05
tags: "javascript"
categories: 
- web前端
---
改变原数组：push、pop、shift、unshift、splice、reverse、sort
其他：join、indexOf、concat、toString、slice、includes、reduce、filter、map、forEach、isArray
 <!-- more -->
#### 不改变原数组的方法
+ array.join()
```
转成字符串，把数组的所有元素放入一个字符串。元素通过指定的分隔符进行分隔,与split()方法相对应。
返回值是字符串，不改变原数组
返回值是排序后的数组，不改变原数组
```
+ array.indexOf(item)
```
找出某个元素在数组中的索引
返回值是所查询的数组元素的下标，不改变原数组
```
+ array.concat(数组)
```
方法用于合并两个或多个数组。此方法不会更改现有数组，而是返回一个新数组。
返回值是合并后的新数组，不改变原数组
```
+ array.toString()
```
把数字转换为字符串/强转字符串调用该方法的对象不是 Number 时抛出 TypeError 异常。
返回值是字符串，不改变原数组
```
+ array.slice(start,end)
```
可从已有的数组中返回选定的元素
返回值是一个新的数组，包含从 start 到 end （不包括该元素）的 arrayObject 中的元素,不改变原数组
```
+ array.includes(item)
```
用来判断一个数组中是否包含一个指定的值，如果包含则返回true，否则返回false；
返回值是boolean值,不改变原数组
```
+ array.reduce(function)
```
方法接收一个函数作为累加器（accumulator），数组中的每个值（从左到右）开始缩减，最终为一个值。
返回计算结果
```
+ arr.filter(function)
```
返回新数组,不影响原数组
```
+ arr.map(function)
```
只是相当于把原数组克隆一份，把克隆的这一份的数组中的对应项改变了,不影响原数组
```
+ arr.forEach(function)
```
遍历数组中的每一项，没有返回值，不支持IE
```
+ Array.isArray
```
判断是否是一个数组
返回值是boolean值
```
#### 改变原数组的方法
+ array.push(item,item2...)
```
可向数组的末尾添加一个或多个元素，它直接修改 arrayObject，而不是创建一个新的数组
返回值是新数组的长度
```
+ array.pop()
```
可向数组的末尾删除一个元素，它直接修改 arrayObject，而不是创建一个新的数组
返回值是删除的元素
```
+ array.shift()
```
删除数组最前面（头部）的元素
返回值是删除的那个元素
```
+ array.unshift(item,item2...)
```
添加一个或多个元素到数组的头部
返回值是新数组的长度
```
+ array.splice(索引，删几个，添加1个，添加2个)
```
通过索引删除某几个元素
返回值是被删除的数组
```
+ array.reverse()
```
数组反转
返回值是相反的数组(原数组和返回值是一样的)
```
+ array.sort()
```
数组排序，可以对按字母顺序进行排序
返回值是排序之后的数组(原数组和返回值是一样的)
```


