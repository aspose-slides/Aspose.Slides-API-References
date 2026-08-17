---
title: ICommentAuthor
second_title: Aspose.Slides for Java API Reference
description: 表示评论的作者。
type: docs
url: /zh/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

表示评论的作者。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getName()](#getName--) | 返回或设置作者的名称。 |
| [setName(String value)](#setName-java.lang.String-) | 返回或设置作者的名称。 |
| [getInitials()](#getInitials--) | 返回或设置作者的首字母缩写。 |
| [setInitials(String value)](#setInitials-java.lang.String-) | 返回或设置作者的首字母缩写。 |
| [getComments()](#getComments--) | 返回此作者所做评论的集合。 |
| [remove()](#remove--) | 从父集合中移除作者。 |
### getName() {#getName--}
```
public abstract String getName()
```

返回或设置作者的名称。读/写 String.

**返回:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

返回或设置作者的名称。读/写 String.

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```

返回或设置作者的首字母缩写。读/写 String.

**返回:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

返回或设置作者的首字母缩写。读/写 String.

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

返回此作者所做评论的集合。只读 [ICommentCollection](../../com.aspose.slides/icommentcollection).

**返回:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```

从父集合中移除作者。