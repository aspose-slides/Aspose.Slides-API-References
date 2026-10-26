---
title: Tint
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل تأثير Tint.
type: docs
url: /ar/com.aspose.slides/tint/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**جميع الواجهات المنفذة:**
[com.aspose.slides.ITint](../../com.aspose.slides/itint), com.aspose.slides.IVisualEffect
```
public final class Tint extends ImageTransformOperation implements ITint, IVisualEffect
```

يمثل تأثير تدرج اللون. يغير قيم لون التأثير نحو/بعيدًا عن درجة اللون بالكمية المحددة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Tint effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [Tint](../../com.aspose.slides/tint) is equal to the current [Tint](../../com.aspose.slides/tint). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final ITintEffectiveData getEffective()
```

يسترجع بيانات تأثير تدرج اللون الفعّالة مع تطبيق الوراثة.

**الإرجاع:**
[ITintEffectiveData](../../com.aspose.slides/itinteffectivedata) - A [ITintEffectiveData](../../com.aspose.slides/itinteffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدد ما إذا كان [Tint](../../com.aspose.slides/tint) المحدد يساوي [Tint](../../com.aspose.slides/tint) الحالي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | The [Tint](../../com.aspose.slides/tint) to compare. |

**الإرجاع:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين.

**الإرجاع:**
int - A hash code for the current object.