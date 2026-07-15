---
title: CommentAuthor
second_title: Aspose.Slides for Android via Java API 參考
description: 表示評論的作者。
type: docs
url: /zh-hant/com.aspose.slides/commentauthor/
---
**繼承：**
java.lang.Object

**已實作的介面：**
[com.aspose.slides.ICommentAuthor](../../com.aspose.slides/icommentauthor), com.aspose.slides.IDOMObject
```
public final class CommentAuthor implements ICommentAuthor, IDOMObject
```

表示評論的作者。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getName()](#getName--) | 返回或設定作者的名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 返回或設定作者的名稱。 |
| [getInitials()](#getInitials--) | 返回或設定作者的縮寫。 |
| [setInitials(String value)](#setInitials-java.lang.String-) | 返回或設定作者的縮寫。 |
| [getComments()](#getComments--) | 返回此作者所作的評論集合。 |
| [remove()](#remove--) | 從父集合中移除作者。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getName() {#getName--}
```
public final String getName()
```


返回或設定作者的名稱。讀寫 String.

**返回：**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


返回或設定作者的名稱。讀寫 String.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public final String getInitials()
```


返回或設定作者的縮寫。讀寫 String.

**返回：**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public final void setInitials(String value)
```


返回或設定作者的縮寫。讀寫 String.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public final ICommentCollection getComments()
```


返回此作者所作的評論集合。唯讀 [ICommentCollection](../../com.aspose.slides/icommentcollection)。

**返回：**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public final void remove()
```


從父集合中移除作者。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject