---
title: ICommentAuthor
second_title: Aspose.Slides for Android via Java API Reference
description: टिप्पणियों के लेखक का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

टिप्पणियों के लेखक का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getName()](#getName--) | लेखक का नाम लौटाता है या सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | लेखक का नाम लौटाता है या सेट करता है। |
| [getInitials()](#getInitials--) | लेखक के प्रारम्भिक अक्षर लौटाता है या सेट करता है। |
| [setInitials(String value)](#setInitials-java.lang.String-) | लेखक के प्रारम्भिक अक्षर लौटाता है या सेट करता है। |
| [getComments()](#getComments--) | इस लेखक द्वारा की गई टिप्पणियों का संग्रह लौटाता है। |
| [remove()](#remove--) | लेखक को पैरेंट कलेक्शन से हटाता है। |
### getName() {#getName--}
```
public abstract String getName()
```

लेखक का नाम लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String.

**रिटर्न्स:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

लेखक का नाम लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```

लेखक के प्रारम्भिक अक्षर लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String.

**रिटर्न्स:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

लेखक के प्रारम्भिक अक्षर लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

केवल पढ़ने योग्य [ICommentCollection](../../com.aspose.slides/icommentcollection)।

**रिटर्न्स:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```

लेखक को पैरेंट कलेक्शन से हटाता है।