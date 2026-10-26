---
title: ICommentAuthor
second_title: Aspose.Slides for Android via Java API Reference
description: 表示註解的作者。
type: docs
url: /zh-hant/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

表示註解的作者。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getName()](#getName--) | 返回或設定作者的名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 返回或設定作者的名稱。 |
| [getInitials()](#getInitials--) | 返回或設定作者的縮寫。 |
| [setInitials(String value)](#setInitials-java.lang.String-) | 返回或設定作者的縮寫。 |
| [getComments()](#getComments--) | 返回此作者所作的註解集合。 |
| [remove()](#remove--) | 從父集合中移除作者。 |
### getName() {#getName--}
```
public abstract String getName()
```

返回或設定作者的名稱。讀寫 String。

**返回:**  
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

返回或設定作者的名稱。讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```

返回或設定作者的縮寫。讀寫 String。

**返回:**  
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

返回或設定作者的縮寫。讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

返回此作者所作的註解集合。唯讀 [ICommentCollection](../../com.aspose.slides/icommentcollection)。

**返回:**  
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```

從父集合中移除作者。