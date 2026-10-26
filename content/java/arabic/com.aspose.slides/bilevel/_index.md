---
title: BiLevel
second_title: المرجع API لـ Aspose.Slides للغة Java
description: يمثّل تأثيرًا ثنائي المستوى أسود/أبيض.
type: docs
url: /ar/com.aspose.slides/bilevel/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

يمثّل تأثيرًا ثنائي-المستوى (أبيض/أسود). تُغيّر الألوان المدخلّة التي تكون سطوعها أقل من قيمة العتبة المحددة إلى اللون الأسود. وتُصبح الألوان التي سطوعها أكبر من أو يساوي القيمة المحددة باللون الأبيض. قيم تأثير ألفا لا تتأثر بهذا التأثير.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getEffective()](#getEffective--) | يحصل على بيانات تأثير ثنائي-المستوى الفعّالة مع تطبيق الوراثة. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدّد ما إذا كان الـ[BiLevel](../../com.aspose.slides/bilevel) المحدد يساوي الـ[BiLevel](../../com.aspose.slides/bilevel) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```


يحصل على بيانات تأثير ثنائي-المستوى الفعّالة مع تطبيق الوراثة.

**الإرجاع:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - كائن من [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدّد ما إذا كان الـ[BiLevel](../../com.aspose.slides/bilevel) المحدد يساوي الـ[BiLevel](../../com.aspose.slides/bilevel) الحالي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الـ[BiLevel](../../com.aspose.slides/bilevel) للمقارنة. |

**الإرجاع:**
boolean - true إذا كانت الكائنات متساوية؛ وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعمل كدالة تجزئة لنوع معين.

**الإرجاع:**
int - رمز تجزئة للكائن الحالي.