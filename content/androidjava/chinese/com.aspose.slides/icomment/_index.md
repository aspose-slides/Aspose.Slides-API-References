---
title: IComment
second_title: Aspose.Slides for Android via Java API 参考
description: 表示幻灯片上的批注。
type: docs
url: /zh/com.aspose.slides/icomment/
---```
public interface IComment
```

表示幻灯片上的批注。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getText()](#getText--) | 返回或设置幻灯片批注的纯文本。 |
| [setText(String value)](#setText-java.lang.String-) | 返回或设置幻灯片批注的纯文本。 |
| [getCreatedTime()](#getCreatedTime--) | 返回或设置批注创建的时间。 |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | 返回或设置批注创建的时间。 |
| [getSlide()](#getSlide--) | 返回或设置批注的父幻灯片。 |
| [getAuthor()](#getAuthor--) | 返回批注的作者。 |
| [getPosition()](#getPosition--) | 返回或设置批注在幻灯片上的位置。 |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | 返回或设置批注在幻灯片上的位置。 |
| [remove()](#remove--) | 从父集合中删除批注及其所有回复。 |
| [getParentComment()](#getParentComment--) | 获取或设置父批注。 |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | 获取或设置父批注。 |
### getText() {#getText--}
```
public abstract String getText()
```


返回或设置幻灯片批注的纯文本。读/写 String。

**返回：**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


返回或设置幻灯片批注的纯文本。读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```


返回或设置批注创建的时间。将此属性设为 java.util.Date(Long.MIN_VALUE) 表示未设置批注时间。读/写 java.util.Date。

--------------------

批注时间是可选参数。

**返回：**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```


返回或设置批注创建的时间。将此属性设为 java.util.Date(Long.MIN_VALUE) 表示未设置批注时间。读/写 java.util.Date。

--------------------

批注时间是可选参数。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```


返回或设置批注的父幻灯片。只读 [ISlide](../../com.aspose.slides/islide)。

**返回：**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```


返回批注的作者。只读 [ICommentAuthor](../../com.aspose.slides/icommentauthor)。

**返回：**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```


返回或设置批注在幻灯片上的位置。读/写 android.graphics.PointF。

**返回：**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```


返回或设置批注在幻灯片上的位置。读/写 android.graphics.PointF。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public abstract void remove()
```


从父集合中删除批注及其所有回复。

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```


获取或设置父批注。读/写 [IComment](../../com.aspose.slides/icomment)。

**返回：**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```


获取或设置父批注。读/写 [IComment](../../com.aspose.slides/icomment)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |