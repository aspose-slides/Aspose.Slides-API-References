---
title: Comment
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a comment on a slide.
type: docs
weight: 126
url: /com.aspose.slides/comment/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

Represents a comment on a slide.
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Returns or sets the plain text of a slide comment. |
| [setText(String value)](#setText-java.lang.String-) | Returns or sets the plain text of a slide comment. |
| [getCreatedTime()](#getCreatedTime--) | Returns or sets the time of a comment creation. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Returns or sets the time of a comment creation. |
| [getSlide()](#getSlide--) | Returns or sets the parent slide of a comment. |
| [getAuthor()](#getAuthor--) | Returns the author of a comment. |
| [getPosition()](#getPosition--) | Returns or sets the position of a comment on a slide. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Returns or sets the position of a comment on a slide. |
| [remove()](#remove--) | Removes comment and all its replies from the parent collection. |
| [getParentComment()](#getParentComment--) | Gets or sets parent comment. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Gets or sets parent comment. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```


Returns or sets the plain text of a slide comment. Read/write String.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Returns or sets the plain text of a slide comment. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```


Returns or sets the time of a comment creation. Setting this property to java.util.Date(Long.MIN\_VALUE) means no comment time is set. Read/write java.util.Date.

--------------------

Comment time is an optional parameter.

**Returns:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```


Returns or sets the time of a comment creation. Setting this property to java.util.Date(Long.MIN\_VALUE) means no comment time is set. Read/write java.util.Date.

--------------------

Comment time is an optional parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```


Returns or sets the parent slide of a comment. Read-only [ISlide](../../com.aspose.slides/islide).

**Returns:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```


Returns the author of a comment. Read-only [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Returns:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final PointF getPosition()
```


Returns or sets the position of a comment on a slide. Read/write android.graphics.PointF.

**Returns:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public final void setPosition(PointF value)
```


Returns or sets the position of a comment on a slide. Read/write android.graphics.PointF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public final void remove()
```


Removes comment and all its replies from the parent collection.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```


Gets or sets parent comment. Read/write [IComment](../../com.aspose.slides/icomment).

**Returns:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```


Gets or sets parent comment. Read/write [IComment](../../com.aspose.slides/icomment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
