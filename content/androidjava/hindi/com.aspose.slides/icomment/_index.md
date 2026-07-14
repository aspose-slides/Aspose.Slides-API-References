---
title: IComment
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: एक स्लाइड पर टिप्पणी का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/icomment/
---```
public interface IComment
```

एक स्लाइड पर टिप्पणी का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
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

### getText() {#getText--}
```
public abstract String getText()
```

स्लाइड टिप्पणी का साधारण टेक्स्ट प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String.

**वापसी:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

स्लाइड टिप्पणी का साधारण टेक्स्ट प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

टिप्पणी निर्माण का समय प्राप्त करता है या सेट करता है। इस प्रॉपर्टी को java.util.Date(Long.MIN_VALUE) पर सेट करने का अर्थ है कि टिप्पणी समय निर्धारित नहीं है। पढ़ने/लिखने योग्य java.util.Date.

--------------------

टिप्पणी समय एक वैकल्पिक पैरामीटर है।

**वापसी:**
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

टिप्पणी निर्माण का समय प्राप्त करता है या सेट करता है। इस प्रॉपर्टी को java.util.Date(Long.MIN_VALUE) पर सेट करने का अर्थ है कि टिप्पणी समय निर्धारित नहीं है। पढ़ने/लिखने योग्य java.util.Date.

--------------------

टिप्पणी समय एक वैकल्पिक पैरामीटर है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```

टिप्पणी का मूल स्लाइड प्राप्त करता है या सेट करता है। केवल-पढ़ने योग्य [ISlide](../../com.aspose.slides/islide).

**वापसी:**
[ISlide](../../com.aspose.slides/islide)

### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

टिप्पणी का लेखक प्राप्त करता है। केवल-पढ़ने योग्य [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**वापसी:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)

### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```

स्लाइड पर टिप्पणी की स्थिति प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य android.graphics.PointF.

**वापसी:**
android.graphics.PointF

### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```

स्लाइड पर टिप्पणी की स्थिति प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य android.graphics.PointF.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public abstract void remove()
```

टिप्पणी और उसकी सभी प्रतिक्रियाओं को मूल संग्रह से हटाता है।

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

मूल टिप्पणी प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [IComment](../../com.aspose.slides/icomment).

**वापसी:**
[IComment](../../com.aspose.slides/icomment)

### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

मूल टिप्पणी प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [IComment](../../com.aspose.slides/icomment).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |