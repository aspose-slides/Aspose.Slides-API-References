---
title: ISlideText
second_title: Aspose.Slides لـ Java مرجع API
description: يمثل النص المستخرج من الشريحة
type: docs
url: /ar/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

يمثل النص المستخرج من الشريحة
## الطرق

| Method | الوصف |
| --- | --- |
| [getText()](#getText--) | النص على أشكال الشريحة |
| [getMasterText()](#getMasterText--) | النص على أشكال الصفحة الرئيسية لهذه الشريحة |
| [getLayoutText()](#getLayoutText--) | النص على أشكال صفحة التخطيط لهذه الشريحة |
| [getNotesText()](#getNotesText--) | النص على أشكال صفحة الملاحظات لهذه الشريحة |
| [getCommentsText()](#getCommentsText--) | نص تعليقات الشريحة |
### getText() {#getText--}
```
public abstract String getText()
```


النص على أشكال الشريحة

**القيمة المرجعة:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```


النص على أشكال الصفحة الرئيسية لهذه الشريحة

**القيمة المرجعة:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```


النص على أشكال صفحة التخطيط لهذه الشريحة

**القيمة المرجعة:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```


النص على أشكال صفحة الملاحظات لهذه الشريحة

**القيمة المرجعة:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```


نص تعليقات الشريحة

--------------------

هذا الحقل يكون فارغًا عندما يتم استخراج النص باستخدام وضع Arranged.

**القيمة المرجعة:**
java.lang.String