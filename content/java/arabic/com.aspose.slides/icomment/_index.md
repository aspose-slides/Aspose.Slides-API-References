---
title: IComment
second_title: Aspose.Slides for Java API Reference
description: يمثل تعليقا على شريحة.
type: docs
url: /ar/com.aspose.slides/icomment/
---```
public interface IComment
```

يمثل تعليقا على شريحة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getText()](#getText--) | إرجاع أو تعيين النص العادي لتعليق الشريحة. |
| [setText(String value)](#setText-java.lang.String-) | إرجاع أو تعيين النص العادي لتعليق الشريحة. |
| [getCreatedTime()](#getCreatedTime--) | إرجاع أو تعيين وقت إنشاء التعليق. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | إرجاع أو تعيين وقت إنشاء التعليق. |
| [getSlide()](#getSlide--) | إرجاع أو تعيين الشريحة الأصلية للتعليق. |
| [getAuthor()](#getAuthor--) | إرجاع مؤلف التعليق. |
| [getPosition()](#getPosition--) | إرجاع أو تعيين موضع التعليق على الشريحة. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | إرجاع أو تعيين موضع التعليق على الشريحة. |
| [remove()](#remove--) | إزالة التعليق وجميع الردود التابعة له من المجموعة الأصلية. |
| [getParentComment()](#getParentComment--) | إرجاع أو تعيين التعليق الأصلي. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | إرجاع أو تعيين التعليق الأصلي. |
### getText() {#getText--}
```
public abstract String getText()
```

إرجاع أو تعيين النص العادي لتعليق الشريحة. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

إرجاع أو تعيين النص العادي لتعليق الشريحة. قراءة/كتابة String.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

إرجاع أو تعيين وقت إنشاء التعليق. تعيين هذه الخاصية إلى java.util.Date(Long.MIN_VALUE) يعني عدم تعيين وقت للتعليق. قراءة/كتابة java.util.Date.

--------------------

وقت التعليق هو معامل اختياري.

**الإرجاع:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

إرجاع أو تعيين وقت إنشاء التعليق. تعيين هذه الخاصية إلى java.util.Date(Long.MIN_VALUE) يعني عدم تعيين وقت للتعليق. قراءة/كتابة java.util.Date.

--------------------

وقت التعليق هو معامل اختياري.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```

إرجاع أو تعيين الشريحة الأصلية للتعليق. قراءة فقط [ISlide](../../com.aspose.slides/islide).

**الإرجاع:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

إرجاع مؤلف التعليق. قراءة فقط [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**الإرجاع:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract Point2D.Float getPosition()
```

إرجاع أو تعيين موضع التعليق على الشريحة. قراءة/كتابة java.awt.geom.Point2D.Float.

**الإرجاع:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public abstract void setPosition(Point2D.Float value)
```

إرجاع أو تعيين موضع التعليق على الشريحة. قراءة/كتابة java.awt.geom.Point2D.Float.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public abstract void remove()
```

إزالة التعليق وجميع الردود التابعة له من المجموعة الأصلية.

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

إرجاع أو تعيين التعليق الأصلي. قراءة/كتابة [IComment](../../com.aspose.slides/icomment).

**الإرجاع:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

إرجاع أو تعيين التعليق الأصلي. قراءة/كتابة [IComment](../../com.aspose.slides/icomment).

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |