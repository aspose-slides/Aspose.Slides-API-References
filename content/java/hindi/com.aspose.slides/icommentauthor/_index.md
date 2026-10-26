---
title: ICommentAuthor
second_title: Aspose.Slides for Java API Reference
description: टिप्पणीकार के लेखक को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

टिप्पणियों के लेखक को दर्शाता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getName()](#getName--) | लेखक का नाम प्राप्त करता है या सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | लेखक का नाम प्राप्त करता है या सेट करता है। |
| [getInitials()](#getInitials--) | लेखक के प्रारंभिक अक्षर प्राप्त करता है या सेट करता है। |
| [setInitials(String value)](#setInitials-java.lang.String-) | लेखक के प्रारंभिक अक्षर प्राप्त करता है या सेट करता है। |
| [getComments()](#getComments--) | इस लेखक द्वारा बनाई गई टिप्पणियों का संग्रह लौटाता है। |
| [remove()](#remove--) | लेखक को मूल संग्रह से हटाता है। |
### getName() {#getName--}
```
public abstract String getName()
```

लेखक का नाम प्राप्त करता है या सेट करता है। Read/write String.

**रिटर्न:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

लेखक का नाम प्राप्त करता है या सेट करता है। Read/write String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```

लेखक के प्रारंभिक अक्षर प्राप्त करता है या सेट करता है। Read/write String.

**रिटर्न:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

लेखक के प्रारंभिक अक्षर प्राप्त करता है या सेट करता है। Read/write String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

लेखक द्वारा बनाई गई टिप्पणियों का संग्रह लौटाता है। Read-only [ICommentCollection](../../com.aspose.slides/icommentcollection).

**रिटर्न:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```

लेखक को मूल संग्रह से हटाता है।