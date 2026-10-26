---
title: ColorReplace
second_title: مرجع API Aspose.Slides للغة Java
description: يمثل تأثير استبدال اللون.
type: docs
url: /ar/com.aspose.slides/colorreplace/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

يمثل تأثير استبدال اللون. جميع ألوان التأثير تُستبدل بلون ثابت. قيم ألفا لا تتأثر.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getColor()](#getColor--) | يعيد تنسيق اللون الذي سيستبدل لون كل بكسل. |
| [getEffective()](#getEffective--) | يحصل على بيانات تأثير استبدال اللون الفعّالة مع تطبيق الوراثة. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان [ColorReplace](../../com.aspose.slides/colorreplace) المحدد يساوي [ColorReplace](../../com.aspose.slides/colorreplace) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


يعيد تنسيق اللون الذي سيستبدل لون كل بكسل. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```


يحصل على بيانات تأثير استبدال اللون الفعّالة مع تطبيق الوراثة.

**الإرجاع:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - A [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


الإصدار. قراءة فقط long.

**الإرجاع:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان [ColorReplace](../../com.aspose.slides/colorreplace) المحدد يساوي [ColorReplace](../../com.aspose.slides/colorreplace) الحالي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | ال[ColorReplace](../../com.aspose.slides/colorreplace) للمقارنة. |

**الإرجاع:**
boolean - true إذا كان الكائنان متساويين؛ وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعمل كدالة تجزئة لنوع معين.

**الإرجاع:**
int - رمز تجزئة للكائن الحالي.