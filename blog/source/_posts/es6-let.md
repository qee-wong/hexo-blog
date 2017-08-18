---
title: es6-let
date: 2017-08-18 19:37:04
tags: let
---

## let

基本用法
ES6新增了let命令，用来声明变量。它的用法类似于var，但是所声明的变量，只在let命令所在的代码块内有效。
``` bash
{
  let a = 10;
  var b = 1;
}

a // ReferenceError: a is not defined.
b // 1
``` 
上面代码在代码块之中，分别用let和var声明了两个变量。然后在代码块之外调用这两个变量，结果let声明的变量报错，var声明的变量返回了正确的值。这表明，let声明的变量只在它所在的代码块有效。
