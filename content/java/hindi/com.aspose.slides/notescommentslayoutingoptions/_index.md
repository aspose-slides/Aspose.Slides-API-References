---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides for Java API संदर्भ
description: निर्यात किए गए दस्तावेज़ में नोट्स और टिप्पणियों की लेआउटिंग के रूप को नियंत्रित करने वाले विकल्प प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/notescommentslayoutingoptions/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

निर्यात किए गए दस्तावेज़ में नोट्स और टिप्पणियों की लेआउटिंग के रूप को नियंत्रित करने वाले विकल्प प्रदान करता है।

## कंस्ट्रक्टर्स

| निर्माता | विवरण |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | डिफ़ॉल्ट कंस्ट्रक्टर। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | लेखक न होने वाली टिप्पणियों की दृश्यता प्राप्त करता है या सेट करता है। |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | लेखक न होने वाली टिप्पणियों की दृश्यता प्राप्त करता है या सेट करता है। |
| [getNotesPosition()](#getNotesPosition--) | पृष्ठ पर नोट्स की स्थिति प्राप्त करता है या सेट करता है। |
| [setNotesPosition(int value)](#setNotesPosition-int-) | पृष्ठ पर नोट्स की स्थिति प्राप्त करता है या सेट करता है। |
| [getCommentsPosition()](#getCommentsPosition--) | पृष्ठ पर टिप्पणियों की स्थिति प्राप्त करता है या सेट करता है। |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | पृष्ठ पर टिप्पणियों की स्थिति प्राप्त करता है या सेट करता है। |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | टिप्पणी क्षेत्र का रंग प्राप्त करता है या सेट करता है (केवल तभी लागू जब टिप्पणियाँ दाईं ओर प्रदर्शित की जाती हैं)। |
| [setCommentsAreaColor(Color value)](#setCommentsAreaColor-java.awt.Color-) | टिप्पणी क्षेत्र का रंग प्राप्त करता है या सेट करता है (केवल तभी लागू जब टिप्पणियाँ दाईं ओर प्रदर्शित की जाती हैं)। |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | पिक्सल में टिप्पणी आउटपुट क्षेत्र की चौड़ाई प्राप्त करता है या सेट करता है (केवल तभी लागू जब टिप्पणियाँ दाईं ओर प्रदर्शित की जाती हैं)। |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | पिक्सल में टिप्पणी आउटपुट क्षेत्र की चौड़ाई प्राप्त करता है या सेट करता है (केवल तभी लागू जब टिप्पणियाँ दाईं ओर प्रदर्शित की जाती हैं)। |

### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

डिफ़ॉल्ट कंस्ट्रक्टर।

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

लेखक न होने वाली टिप्पणियों की दृश्यता प्राप्त करता है या सेट करता है। यदि true है तो टिप्पणियाँ प्रदर्शित की जाएँगी। (केवल तभी लागू जब टिप्पणियाँ प्रदर्शित की जाती हैं)।

--------------------

डिफ़ॉल्ट मान **false** है।

**रिटर्न:**  
boolean

### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

लेखक न होने वाली टिप्पणियों की दृश्यता प्राप्त करता है या सेट करता है। यदि true है तो टिप्पणियाँ प्रदर्शित की जाएँगी। (केवल तभी लागू जब टिप्पणियाँ प्रदर्शित की जाती हैं)।

--------------------

डिफ़ॉल्ट मान **false** है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```

पृष्ठ पर नोट्स की स्थिति प्राप्त करता है या सेट करता है।

--------------------

डिफ़ॉल्ट **NotesPositions.None** है।

**रिटर्न:**  
int

### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

पृष्ठ पर नोट्स की स्थिति प्राप्त करता है या सेट करता है।

--------------------

डिफ़ॉल्ट **NotesPositions.None** है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

पृष्ठ पर टिप्पणियों की स्थिति प्राप्त करता है या सेट करता है।

--------------------

डिफ़ॉल्ट **CommentsPositions.None** है।

**रिटर्न:**  
int

### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

पृष्ठ पर टिप्पणियों की स्थिति प्राप्त करता है या सेट करता है।

--------------------

डिफ़ॉल्ट **CommentsPositions.None** है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Color getCommentsAreaColor()
```

टिप्पणी क्षेत्र का रंग प्राप्त करता है या सेट करता है (केवल तभी लागू जब टिप्पणियाँ दाईं ओर प्रदर्शित की जाती हैं)।

--------------------

डिफ़ॉल्ट **Color.SkyBlue** है।

**रिटर्न:**  
java.awt.Color

### setCommentsAreaColor(Color value) {#setCommentsAreaColor-java.awt.Color-}
```
public final void setCommentsAreaColor(Color value)
```

टिप्पणी क्षेत्र का रंग प्राप्त करता है या सेट करता है (केवल तभी लागू जब टिप्पणियाँ दाईं ओर प्रदर्शित की जाती हैं)।

--------------------

डिफ़ॉल्ट **Color.SkyBlue** है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.awt.Color |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

पिक्सल में टिप्पणी आउटपुट क्षेत्र की चौड़ाई प्राप्त करता है या सेट करता है (केवल तभी लागू जब टिप्पणियाँ दाईं ओर प्रदर्शित की जाती हैं)।

--------------------

न्यूनतम और डिफ़ॉल्ट मान **150** है।

**रिटर्न:**  
int

### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

पिक्सल में टिप्पणी आउटपुट क्षेत्र की चौड़ाई प्राप्त करता है या सेट करता है (केवल तभी लागू जब टिप्पणियाँ दाईं ओर प्रदर्शित की जाती हैं)।

--------------------

न्यूनतम और डिफ़ॉल्ट मान **150** है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |