---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: निर्यातित दस्तावेज़ में नोट्स और टिप्पणियों की लेआउटिंग के रूप को नियंत्रित करने के विकल्प प्रदान करता है।
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

निर्यातित दस्तावेज़ में नोट्स और टिप्पणियों की लेआउटिंग के रूप को नियंत्रित करने के विकल्प प्रदान करता है।

## कन्स्ट्रक्टर्स

| निर्माता | विवरण |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | डिफ़ॉल्ट कन्स्ट्रक्टर। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | लेखक नहीं रखने वाली टिप्पणियों की दृश्यता प्राप्त करता है या सेट करता है। |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | लेखक नहीं रखने वाली टिप्पणियों की दृश्यता प्राप्त करता है या सेट करता है। |
| [getNotesPosition()](#getNotesPosition--) | पृष्ठ पर नोट्स की स्थिति प्राप्त करता है या सेट करता है। |
| [setNotesPosition(int value)](#setNotesPosition-int-) | पृष्ठ पर नोट्स की स्थिति प्राप्त करता है या सेट करता है। |
| [getCommentsPosition()](#getCommentsPosition--) | पृष्ठ पर टिप्पणियों की स्थिति प्राप्त करता है या सेट करता है। |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | पृष्ठ पर टिप्पणियों की स्थिति प्राप्त करता है या सेट करता है। |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | टिप्पणी क्षेत्र का रंग प्राप्त करता है या सेट करता है (केवल तब लागू जब टिप्पणियाँ दाएँ側 प्रदर्शित हों)। |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | टिप्पणी क्षेत्र का रंग प्राप्त करता है या सेट करता है (केवल तब लागू जब टिप्पणियाँ दाएँ側 प्रदर्शित हों)। |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | पिक्सेल में टिप्पणी आउटपुट क्षेत्र की चौड़ाई प्राप्त करता है या सेट करता है (केवल तब लागू जब टिप्पणियाँ दाएँ側 प्रदर्शित हों)। |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | पिक्सेल में टिप्पणी आउटपुट क्षेत्र की चौड़ाई प्राप्त करता है या सेट करता है (केवल तब लागू जब टिप्पणियाँ दाएँ側 प्रदर्शित हों)। |

### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

डिफ़ॉल्ट कन्स्ट्रक्टर।

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

लेखक नहीं रखने वाली टिप्पणियों की दृश्यता प्राप्त करता है या सेट करता है। यदि true है तो टिप्पणियाँ प्रदर्शित की जाएँगी। (केवल तब लागू जब टिप्पणियाँ प्रदर्शित हों)।

--------------------

डिफ़ॉल्ट मान **false** है।

**वापसी:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

लेखक नहीं रखने वाली टिप्पणियों की दृश्यता प्राप्त करता है या सेट करता है। यदि true है तो टिप्पणियाँ प्रदर्शित की जाएँगी। (केवल तब लागू जब टिप्पणियाँ प्रदर्शित हों)।

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

**वापसी:**
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

**वापसी:**
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
public final Integer getCommentsAreaColor()
```

टिप्पणी क्षेत्र का रंग प्राप्त करता है या सेट करता है (केवल तब लागू जब टिप्पणियाँ दाएँ側 प्रदर्शित हों)।

--------------------

डिफ़ॉल्ट **SkyBlue** है।

**वापसी:**
java.lang.Integer
### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```

टिप्पणी क्षेत्र का रंग प्राप्त करता है या सेट करता है (केवल तब लागू जब टिप्पणियाँ दाएँ側 प्रदर्शित हों)।

--------------------

डिफ़ॉल्ट **SkyBlue** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

पिक्सेल में टिप्पणी आउटपुट क्षेत्र की चौड़ाई प्राप्त करता है या सेट करता है (केवल तब लागू जब टिप्पणियाँ दाएँ側 प्रदर्शित हों)।

--------------------

न्यूनतम और डिफ़ॉल्ट मान **150** है।

**वापसी:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

पिक्सेल में टिप्पणी आउटपुट क्षेत्र की चौड़ाई प्राप्त करता है या सेट करता है (केवल तब लागू जब टिप्पणियाँ दाएँ側 प्रदर्शित हों)।

--------------------

न्यूनतम और डिफ़ॉल्ट मान **150** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |