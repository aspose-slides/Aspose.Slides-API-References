---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يوفر خيارات تتحكم في مظهر تخطيط الملاحظات والتعليقات في المستند المُصدَّر.
type: docs
url: /ar/com.aspose.slides/notescommentslayoutingoptions/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُطبقة:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

يوفر خيارات تتحكم في مظهر تخطيط الملاحظات والتعليقات في المستند المُصدّر.
## المُنشئات

| Constructor | Description |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | المُنشئ الافتراضي. |
## الطرق

| Method | Description |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | يحصل أو يضبط ظهور التعليقات التي لا تمتلك مؤلفًا. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | يحصل أو يضبط ظهور التعليقات التي لا تمتلك مؤلفًا. |
| [getNotesPosition()](#getNotesPosition--) | يحصل أو يضبط موضع الملاحظات على الصفحة. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | يحصل أو يضبط موضع الملاحظات على الصفحة. |
| [getCommentsPosition()](#getCommentsPosition--) | يحصل أو يضبط موضع التعليقات على الصفحة. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | يحصل أو يضبط موضع التعليقات على الصفحة. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | يحصل أو يضبط لون منطقة التعليقات (يطبق فقط إذا تم عرض التعليقات على اليمين). |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | يحصل أو يضبط لون منطقة التعليقات (يطبق فقط إذا تم عرض التعليقات على اليمين). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | يحصل أو يضبط عرض منطقة إخراج التعليق بالبكسل (يطبق فقط إذا تم عرض التعليقات على اليمين). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | يحصل أو يضبط عرض منطقة إخراج التعليق بالبكسل (يطبق فقط إذا تم عرض التعليقات على اليمين). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

المُنشئ الافتراضي.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

يحصل أو يضبط ظهور التعليقات التي لا تمتلك مؤلفًا. إذا كان true فسيتم عرض التعليقات. (يطبق فقط إذا تم عرض التعليقات).

--------------------

القيمة الافتراضية هي **false**.

**الإرجاع:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

يحصل أو يضبط ظهور التعليقات التي لا تمتلك مؤلفًا. إذا كان true فسيتم عرض التعليقات. (يطبق فقط إذا تم عرض التعليقات).

--------------------

القيمة الافتراضية هي **false**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```

يحصل أو يضبط موضع الملاحظات على الصفحة.

--------------------

القيمة الافتراضية هي **NotesPositions.None**.

**الإرجاع:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

يحصل أو يضبط موضع الملاحظات على الصفحة.

--------------------

القيمة الافتراضية هي **NotesPositions.None**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

يحصل أو يضبط موضع التعليقات على الصفحة.

--------------------

القيمة الافتراضية هي **CommentsPositions.None**.

**الإرجاع:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

يحصل أو يضبط موضع التعليقات على الصفحة.

--------------------

القيمة الافتراضية هي **CommentsPositions.None**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Integer getCommentsAreaColor()
```

يحصل أو يضبط لون منطقة التعليقات (يطبق فقط إذا تم عرض التعليقات على اليمين).

--------------------

القيمة الافتراضية هي **SkyBlue**.

**الإرجاع:**
java.lang.Integer
### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```

يحصل أو يضبط لون منطقة التعليقات (يطبق فقط إذا تم عرض التعليقات على اليمين).

--------------------

القيمة الافتراضية هي **SkyBlue**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

يحصل أو يضبط عرض منطقة إخراج التعليق بالبكسل (يطبق فقط إذا تم عرض التعليقات على اليمين).

--------------------

القيمة الدنيا والافتراضية هي **150**.

**الإرجاع:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

يحصل أو يضبط عرض منطقة إخراج التعليق بالبكسل (يطبق فقط إذا تم عرض التعليقات على اليمين).

--------------------

القيمة الدنيا والافتراضية هي **150**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |