---
title: IComment
second_title: Aspose.Slides for Java API संदर्भ
description: स्लाइड पर एक टिप्पणी का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/icomment/
---```
public interface IComment
```

स्लाइड पर एक टिप्पणी का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getText()](#getText--) | एक स्लाइड टिप्पणी का सामान्य पाठ लौटाता है या सेट करता है। |
| [setText(String value)](#setText-java.lang.String-) | एक स्लाइड टिप्पणी का सामान्य पाठ लौटाता है या सेट करता है। |
| [getCreatedTime()](#getCreatedTime--) | एक टिप्पणी के निर्माण का समय लौटाता है या सेट करता है। |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | एक टिप्पणी के निर्माण का समय लौटाता है या सेट करता है। |
| [getSlide()](#getSlide--) | एक टिप्पणी की पैरेंट स्लाइड लौटाता है या सेट करता है। |
| [getAuthor()](#getAuthor--) | एक टिप्पणी के लेखक को लौटाता है। |
| [getPosition()](#getPosition--) | स्लाइड पर टिप्पणी की स्थिति लौटाता है या सेट करता है। |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | स्लाइड पर टिप्पणी की स्थिति लौटाता है या सेट करता है। |
| [remove()](#remove--) | टिप्पणी और उसकी सभी प्रतिक्रियाओं को पैरेंट संग्रह से हटाता है। |
| [getParentComment()](#getParentComment--) | पैरेंट टिप्पणी को प्राप्त करता है या सेट करता है। |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | पैरेंट टिप्पणी को प्राप्त करता है या सेट करता है। |
### getText() {#getText--}
```
public abstract String getText()
```

एक स्लाइड टिप्पणी का सामान्य पाठ लौटाता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न्स:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

एक स्लाइड टिप्पणी का सामान्य पाठ लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

एक टिप्पणी के निर्माण का समय लौटाता है या सेट करता है। इस गुण को java.util.Date(Long.MIN_VALUE) पर सेट करने का अर्थ है कोई टिप्पणी समय सेट नहीं है। पढ़ें/लिखें java.util.Date.

--------------------

टिप्पणी समय एक वैकल्पिक पैरामीटर है।

**रिटर्न्स:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

एक टिप्पणी के निर्माण का समय लौटाता है या सेट करता है। इस गुण को java.util.Date(Long.MIN_VALUE) पर सेट करने का अर्थ है कोई टिप्पणी समय सेट नहीं है। पढ़ें/लिखें java.util.Date.

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

एक टिप्पणी की पैरेंट स्लाइड लौटाता है या सेट करता है। केवल-पढ़ने योग्य [ISlide](../../com.aspose.slides/islide).

**रिटर्न्स:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

एक टिप्पणी के लेखक को लौटाता है। केवल-पढ़ने योग्य [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**रिटर्न्स:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract Point2D.Float getPosition()
```

स्लाइड पर टिप्पणी की स्थिति लौटाता है या सेट करता है। पढ़ें/लिखें java.awt.geom.Point2D.Float.

**रिटर्न्स:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public abstract void setPosition(Point2D.Float value)
```

स्लाइड पर टिप्पणी की स्थिति लौटाता है या सेट करता है। पढ़ें/लिखें java.awt.geom.Point2D.Float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### remove() {#remove--}
```
public abstract void remove()
```

टिप्पणी और उसकी सभी प्रतिक्रियाओं को पैरेंट संग्रह से हटाता है।

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

पैरेंट टिप्पणी को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IComment](../../com.aspose.slides/icomment).

**रिटर्न्स:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

पैरेंट टिप्पणी को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IComment](../../com.aspose.slides/icomment).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |