---
title: IComment
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a comment on a slide.
type: docs
url: /zh-hant/com.aspose.slides/icomment/
---```
public interface IComment
```

代表投影片上的註解。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getText()](#getText--) | 取得或設定投影片註解的純文字。 |
| [setText(String value)](#setText-java.lang.String-) | 取得或設定投影片註解的純文字。 |
| [getCreatedTime()](#getCreatedTime--) | 取得或設定註解建立的時間。 |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | 取得或設定註解建立的時間。 |
| [getSlide()](#getSlide--) | 取得或設定註解的父投影片。 |
| [getAuthor()](#getAuthor--) | 取得註解的作者。 |
| [getPosition()](#getPosition--) | 取得或設定註解在投影片上的位置。 |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | 取得或設定註解在投影片上的位置。 |
| [remove()](#remove--) | 從父集合中移除註解及其所有回覆。 |
| [getParentComment()](#getParentComment--) | 取得或設定父註解。 |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | 取得或設定父註解。 |
### getText() {#getText--}
```
public abstract String getText()
```


取得或設定投影片註解的純文字。 讀寫 String.

**回傳:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


取得或設定投影片註解的純文字。 讀寫 String.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```


取得或設定註解建立的時間。 將此屬性設定為 java.util.Date(Long.MIN\_VALUE) 表示未設定註解時間。 讀寫 java.util.Date。

--------------------

註解時間是可選參數。

**回傳:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```


取得或設定註解建立的時間。 將此屬性設定為 java.util.Date(Long.MIN\_VALUE) 表示未設定註解時間。 讀寫 java.util.Date。

--------------------

註解時間是可選參數。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```


取得或設定註解的父投影片。 唯讀 [ISlide](../../com.aspose.slides/islide)。

**回傳:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```


取得註解的作者。 唯讀 [ICommentAuthor](../../com.aspose.slides/icommentauthor)。

**回傳:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```


取得或設定註解在投影片上的位置。 讀寫 android.graphics.PointF。

**回傳:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```


取得或設定註解在投影片上的位置。 讀寫 android.graphics.PointF。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public abstract void remove()
```


從父集合中移除註解及其所有回覆。

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```


取得或設定父註解。 讀寫 [IComment](../../com.aspose.slides/icomment)。

**回傳:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```


取得或設定父註解。 讀寫 [IComment](../../com.aspose.slides/icomment)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |