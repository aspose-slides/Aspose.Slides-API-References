---
title: IComment
second_title: Aspose.Slides for Java API Reference
description: Represents a comment on a slide.
type: docs
url: /fa/com.aspose.slides/icomment/
---```
public interface IComment
```

نمایانگر یک نظر بر روی اسلاید است.
## متدها

| متد | توضیح |
| --- | --- |
| [getText()](#getText--) | متن ساده یک نظر اسلاید را برمی‌گرداند یا تنظیم می‌کند. |
| [setText(String value)](#setText-java.lang.String-) | متن ساده یک نظر اسلاید را برمی‌گرداند یا تنظیم می‌کند. |
| [getCreatedTime()](#getCreatedTime--) | زمان ایجاد یک نظر را برمی‌گرداند یا تنظیم می‌کند. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | زمان ایجاد یک نظر را برمی‌گرداند یا تنظیم می‌کند. |
| [getSlide()](#getSlide--) | اسلاید والد یک نظر را برمی‌گرداند یا تنظیم می‌کند. |
| [getAuthor()](#getAuthor--) | نویسنده یک نظر را برمی‌گرداند. |
| [getPosition()](#getPosition--) | موقعیت یک نظر در اسلاید را برمی‌گرداند یا تنظیم می‌کند. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | موقعیت یک نظر در اسلاید را برمی‌گرداند یا تنظیم می‌کند. |
| [remove()](#remove--) | نظر و تمام پاسخ‌های آن را از مجموعه والد حذف می‌کند. |
| [getParentComment()](#getParentComment--) | نظر والد را برمی‌گیرد یا تنظیم می‌کند. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | نظر والد را برمی‌گیرد یا تنظیم می‌کند. |
### getText() {#getText--}
```
public abstract String getText()
```


متن ساده یک نظر اسلاید را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**بازگشت:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


متن ساده یک نظر اسلاید را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```


زمان ایجاد یک نظر را برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی به java.util.Date(Long.MIN_VALUE) به این معنی است که زمان نظر تنظیم نشده است. قابل خواندن/نوشتن java.util.Date.

--------------------

زمان نظر یک پارامتر اختیاری است.

**بازگشت:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```


زمان ایجاد یک نظر را برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی به java.util.Date(Long.MIN_VALUE) به این معنی است که زمان نظر تنظیم نشده است. قابل خواندن/نوشتن java.util.Date.

--------------------

زمان نظر یک پارامتر اختیاری است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```


اسلاید والد یک نظر را برمی‌گرداند یا تنظیم می‌کند. فقط خواندنی [ISlide](../../com.aspose.slides/islide).

**بازگشت:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```


نویسنده یک نظر را برمی‌گرداند. فقط خواندنی [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**بازگشت:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract Point2D.Float getPosition()
```


موقعیت یک نظر در اسلاید را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن java.awt.geom.Point2D.Float.

**بازگشت:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public abstract void setPosition(Point2D.Float value)
```


موقعیت یک نظر در اسلاید را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن java.awt.geom.Point2D.Float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public abstract void remove()
```


نظر و تمام پاسخ‌های آن را از مجموعه والد حذف می‌کند.

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```


نظر والد را برمی‌گیرد یا تنظیم می‌کند. قابل خواندن/نوشتن [IComment](../../com.aspose.slides/icomment).

**بازگشت:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```


نظر والد را برمی‌گیرد یا تنظیم می‌کند. قابل خواندن/نوشتن [IComment](../../com.aspose.slides/icomment).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |