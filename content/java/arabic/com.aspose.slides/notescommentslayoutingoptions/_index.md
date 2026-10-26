---
title: NotesCommentsLayoutingOptions
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للـ Java
description: يوفر خيارات تتحكم في مظهر تخطيط الملاحظات والتعليقات في المستند المُصدَّر.
type: docs
url: /ar/com.aspose.slides/notescommentslayoutingoptions/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

يوفر خيارات تتحكم في مظهر تخطيط الملاحظات والتعليقات في المستند المُصدَّر.
## البناؤون

| المنشئ | الوصف |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | المنشئ الافتراضي. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | يحصل أو يعين رؤية التعليقات التي لا يمتلكها مؤلف. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | يحصل أو يعين رؤية التعليقات التي لا يمتلكها مؤلف. |
| [getNotesPosition()](#getNotesPosition--) | يحصل أو يعين موضع الملاحظات على الصفحة. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | يحصل أو يعين موضع الملاحظات على الصفحة. |
| [getCommentsPosition()](#getCommentsPosition--) | يحصل أو يعين موضع التعليقات على الصفحة. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | يحصل أو يعين موضع التعليقات على الصفحة. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | يحصل أو يعين لون منطقة التعليقات (يطبق فقط إذا تم عرض التعليقات على اليمين). |
| [setCommentsAreaColor(Color value)](#setCommentsAreaColor-java.awt.Color-) | يحصل أو يعين لون منطقة التعليقات (يطبق فقط إذا تم عرض التعليقات على اليمين). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | يحصل أو يعين عرض منطقة إخراج التعليق بالبكسل (يطبق فقط إذا تم عرض التعليقات على اليمين). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | يحصل أو يعين عرض منطقة إخراج التعليق بالبكسل (يطبق فقط إذا تم عرض التعليقات على اليمين). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```


المنشئ الافتراضي.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```


يحصل أو يعين رؤية التعليقات التي لا يمتلكها مؤلف. إذا كان true فسيتم عرض التعليقات. (يطبق فقط إذا كانت التعليقات معروضة).

--------------------

القيمة الافتراضية هي **false**.

**الإرجاع:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```


يحصل أو يعين رؤية التعليقات التي لا يمتلكها مؤلف. إذا كان true فسيتم عرض التعليقات. (يطبق فقط إذا كانت التعليقات معروضة).

--------------------

القيمة الافتراضية هي **false**.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```


يحصل أو يعين موضع الملاحظات على الصفحة.

--------------------

القيمة الافتراضية هي **NotesPositions.None**.

**الإرجاع:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```


يحصل أو يعين موضع الملاحظات على الصفحة.

--------------------

القيمة الافتراضية هي **NotesPositions.None**.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```


يحصل أو يعين موضع التعليقات على الصفحة.

--------------------

القيمة الافتراضية هي **CommentsPositions.None**.

**الإرجاع:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```


يحصل أو يعين موضع التعليقات على الصفحة.

--------------------

القيمة الافتراضية هي **CommentsPositions.None**.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Color getCommentsAreaColor()
```


يحصل أو يعين لون منطقة التعليقات (يطبق فقط إذا تم عرض التعليقات على اليمين).

--------------------

القيمة الافتراضية هي **Color.SkyBlue**.

**الإرجاع:**
java.awt.Color
### setCommentsAreaColor(Color value) {#setCommentsAreaColor-java.awt.Color-}
```
public final void setCommentsAreaColor(Color value)
```


يحصل أو يعين لون منطقة التعليقات (يطبق فقط إذا تم عرض التعليقات على اليمين).

--------------------

القيمة الافتراضية هي **Color.SkyBlue**.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.awt.Color |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```


يحصل أو يعين عرض منطقة إخراج التعليق بالبكسل (يطبق فقط إذا تم عرض التعليقات على اليمين).

--------------------

القيمة الدنيا والافتراضية هي **150**.

**الإرجاع:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```


يحصل أو يعين عرض منطقة إخراج التعليق بالبكسل (يطبق فقط إذا تم عرض التعليقات على اليمين).

--------------------

القيمة الدنيا والافتراضية هي **150**.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |