---
title: IComment
second_title: Aspose.Slides for Android via Java API Reference
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
| [getText()](#getText--) | مقدار متن ساده یک نظر اسلاید را بازمی‌گرداند یا تنظیم می‌کند. |
| [setText(String value)](#setText-java.lang.String-) | مقدار متن ساده یک نظر اسلاید را بازمی‌گرداند یا تنظیم می‌کند. |
| [getCreatedTime()](#getCreatedTime--) | مقدار زمان ایجاد یک نظر را بازمی‌گرداند یا تنظیم می‌کند. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | مقدار زمان ایجاد یک نظر را بازمی‌گرداند یا تنظیم می‌کند. |
| [getSlide()](#getSlide--) | اسلاید والد یک نظر را بازمی‌گرداند یا تنظیم می‌کند. |
| [getAuthor()](#getAuthor--) | نویسنده یک نظر را بازمی‌گرداند. |
| [getPosition()](#getPosition--) | موقعیت یک نظر بر روی اسلاید را بازمی‌گرداند یا تنظیم می‌کند. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | موقعیت یک نظر بر روی اسلاید را بازمی‌گرداند یا تنظیم می‌کند. |
| [remove()](#remove--) | نظر و تمام پاسخ‌های آن را از مجموعه والد حذف می‌کند. |
| [getParentComment()](#getParentComment--) | نظر والد را دریافت یا تنظیم می‌کند. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | نظر والد را دریافت یا تنظیم می‌کند. |
### getText() {#getText--}
```
public abstract String getText()
```

مقدار متن ساده یک نظر اسلاید را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن String.

**بازگشت:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

مقدار متن ساده یک نظر اسلاید را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

مقدار زمان ایجاد یک نظر را بازمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی به java.util.Date(Long.MIN_VALUE) به معنای عدم تنظیم زمان نظر است. خواندنی/قابل‌نوشتن java.util.Date.

--------------------

زمان نظر یک پارامتر اختیاری است.

**بازگشت:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

مقدار زمان ایجاد یک نظر را بازمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی به java.util.Date(Long.MIN_VALUE) به معنای عدم تنظیم زمان نظر است. خواندنی/قابل‌نوشتن java.util.Date.

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

اسلاید والد یک نظر را بازمی‌گرداند یا تنظیم می‌کند. فقط-خواندنی [ISlide](../../com.aspose.slides/islide).

**بازگشت:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

نویسنده یک نظر را بازمی‌گرداند. فقط-خواندنی [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**بازگشت:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```

موقعیت یک نظر بر روی اسلاید را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن android.graphics.PointF.

**بازگشت:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```

موقعیت یک نظر بر روی اسلاید را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن android.graphics.PointF.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### remove() {#remove--}
```
public abstract void remove()
```

نظر و تمام پاسخ‌های آن را از مجموعه والد حذف می‌کند.

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

نظر والد را دریافت یا تنظیم می‌کند. خواندنی/قابل‌نوشتن [IComment](../../com.aspose.slides/icomment).

**بازگشت:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

نظر والد را دریافت یا تنظیم می‌کند. خواندنی/قابل‌نوشتن [IComment](../../com.aspose.slides/icomment).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |