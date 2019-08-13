---
title: git-issues
date: 2019-08-13 13:46:10
tags:
---

### Git 提示fatal: remote origin already exists 错误解决办法
```
git remote add origin 提示错误：
fatal: remote origin already exists. 
```
#### 解决方法
```
$ git remote rm origin
$ git remote add origin git@github.com:FBing/java-code-generator
```