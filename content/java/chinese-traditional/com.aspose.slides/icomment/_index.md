---
title: IComment
second_title: Aspose.Slides 的 Java API 參考
description: 表示投影片上的評論。
type: docs
url: /zh-hant/com.aspose.slides/icomment/
---```
public interface IComment
```

表示投影片上的評論。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getText()](#getText--) | 返回或設定投影片評論的純文字。 |
| [setText(String value)](#setText-java.lang.String-) | 返回或設定投影片評論的純文字。 |
| [getCreatedTime()](#getCreatedTime--) | 返回或設定評論建立的時間。 |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | 返回或設定評論建立的時間。 |
| [getSlide()](#getSlide--) | 返回或設定評論的父投影片。 |
| [getAuthor()](#getAuthor--) | 返回評論的作者。 |
| [getPosition()](#getPosition--) | 返回或設定評論在投影片上的位置。 |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | 返回或設定評論在投影片上的位置。 |
| [remove()](#remove--) | 從父集合中移除評論及其所有回覆。 |
| [getParentComment()](#getParentComment--) | 取得或設定父評論。 |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | 取得或設定父評論。 |
### getText() {#getText--}
```
public abstract String getText()
```

返回或設定投影片評論的純文字。讀/寫 String。

**返回:**  
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

返回或設定投影片評論的純文字。讀/寫 String。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

返回或設定評論建立的時間。將此屬性設為 java.util.Date(Long.MIN\_VALUE) 表示未設定評論時間。讀/寫 java.util.Date。

--------------------

評論時間是可選參數。

**返回:**  
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

返回或設定評論建立的時間。將此屬性設為 java.util.Date(Long.MIN\_VALUE) 表示未設定評論時間。讀/寫 java.util.Date。

--------------------

評論時間是可選參數。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |
### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```

返回或設定評論的父投影片。唯讀 [ISlide](../../com.aspose.slides/islide)。

**返回:**  
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

返回評論的作者。唯讀 [ICommentAuthor](../../com.aspose.slides/icommentauthor)。

**返回:**  
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract Point2D.Float getPosition()
```

返回或設定評論在投影片上的位置。讀/寫 java.awt.geom.Point2D.Float。

**返回:**  
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public abstract void setPosition(Point2D.Float value)
```

返回或設定評論在投影片上的位置。讀/寫 java.awt.geom.Point2D.Float。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### remove() {#remove--}
```
public abstract void remove()
```

從父集合中移除評論及其所有回覆。
### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

取得或設定父評論。讀/寫 [IComment](../../com.aspose.slides/icomment)。

**返回:**  
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

取得或設定父評論。讀/寫 [IComment](../../com.aspose.slides/icomment)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |