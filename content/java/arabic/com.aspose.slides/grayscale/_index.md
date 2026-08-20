---
title: GrayScale
second_title: مرجع API لأسبوز سلايدز لجافا
description: يمثل تأثير التدرج الرمادي.
type: docs
url: /ar/com.aspose.slides/grayscale/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

يمثل تأثير التدرج الرمادي. يحول جميع قيم ألوان التأثير إلى ظل من الرمادي، يتطابق مع إضاءةها. قيم α (الشفافية) للتأثير لا تتأثر.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getEffective()](#getEffective--) | يحصل على بيانات تأثير التدرج الرمادي الفعّال مع تطبيق الوراثة. |
| [equals(Object obj)](#equals-java.lang.Object-) | يقيم ما إذا كان الـ [GrayScale](../../com.aspose.slides/grayscale) المحدد يساوي الـ [GrayScale](../../com.aspose.slides/grayscale) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين. |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```

يحصل على بيانات تأثير التدرج الرمادي الفعّال مع تطبيق الوراثة.

**القيمة المرجعة:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يقيم ما إذا كان الـ [GrayScale](../../com.aspose.slides/grayscale) المحدد يساوي الـ [GrayScale](../../com.aspose.slides/grayscale) الحالي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الـ [GrayScale](../../com.aspose.slides/grayscale) للمقارنة. |

**القيمة المرجعة:**
boolean - true إذا كانت الكائنات متساوية؛ وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين.

**القيمة المرجعة:**
int - رمز تجزئة للكائن الحالي.