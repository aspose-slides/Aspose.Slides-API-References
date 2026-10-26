---
title: IComment
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a comment on a slide.
type: docs
url: /ar/com.aspose.slides/icomment/
---```
public interface IComment
```

يمثل تعليقًا على شريحة.
## الطرق

| Method | Description |
| --- | --- |
| [getText()](#getText--) | يرجع أو يضبط النص العادي لتعليق الشريحة. |
| [setText(String value)](#setText-java.lang.String-) | يرجع أو يضبط النص العادي لتعليق الشريحة. |
| [getCreatedTime()](#getCreatedTime--) | يرجع أو يضبط وقت إنشاء التعليق. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | يرجع أو يضبط وقت إنشاء التعليق. |
| [getSlide()](#getSlide--) | يرجع أو يضبط الشريحة الأصلية للتعليق. |
| [getAuthor()](#getAuthor--) | يرجع مؤلف التعليق. |
| [getPosition()](#getPosition--) | يرجع أو يضبط موضع التعليق على الشريحة. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | يرجع أو يضبط موضع التعليق على الشريحة. |
| [remove()](#remove--) | يزيل التعليق وجميع ردوده من المجموعة الأصلية. |
| [getParentComment()](#getParentComment--) | يحصل أو يضبط التعليق الأصل. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | يحصل أو يضبط التعليق الأصل. |
### getText() {#getText--}
```
public abstract String getText()
```

يرجع أو يضبط النص العادي لتعليق الشريحة. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

يرجع أو يضبط النص العادي لتعليق الشريحة. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

يرجع أو يضبط وقت إنشاء التعليق. تعيين هذه الخاصية إلى java.util.Date(Long.MIN_VALUE) يعني عدم تحديد وقت التعليق. قراءة/كتابة java.util.Date.

--------------------

وقت التعليق هو معامل اختياري.

**الإرجاع:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

يرجع أو يضبط وقت إنشاء التعليق. تعيين هذه الخاصية إلى java.util.Date(Long.MIN_VALUE) يعني عدم تحديد وقت التعليق. قراءة/كتابة java.util.Date.

--------------------

وقت التعليق هو معامل اختياري.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |
### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```

يرجع أو يضبط الشريحة الأصلية للتعليق. قراءة فقط [ISlide](../../com.aspose.slides/islide).

**الإرجاع:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

يرجع مؤلف التعليق. قراءة فقط [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**الإرجاع:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```

يرجع أو يضبط موضع التعليق على الشريحة. قراءة/كتابة android.graphics.PointF.

**الإرجاع:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```

يرجع أو يضبط موضع التعليق على الشريحة. قراءة/كتابة android.graphics.PointF.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### remove() {#remove--}
```
public abstract void remove()
```

يزيل التعليق وجميع ردوده من المجموعة الأصلية.
### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

يحصل أو يضبط التعليق الأصل. قراءة/كتابة [IComment](../../com.aspose.slides/icomment).

**الإرجاع:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

يحصل أو يضبط التعليق الأصل. قراءة/كتابة [IComment](../../com.aspose.slides/icomment).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |