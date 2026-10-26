---
title: BiLevel
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل تأثيرًا ثنائي المستوى بالأبيض والأسود.
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

يمثل تأثير Bi-Level (أبيض/أسود). يتم تغيير ألوان الإدخال التي يكون سطوعها أقل من قيمة العتبة المحددة إلى اللون الأسود. يتم تعيين ألوان الإدخال التي يكون سطوعها أكبر من أو مساوي للقيمة المحددة إلى اللون الأبيض. لا تتأثر قيم تأثير ألفا بهذا التأثير.
## Methods

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | يحصل على بيانات تأثير Bi-Level الفعلية مع تطبيق الوراثة. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان [BiLevel](../../com.aspose.slides/bilevel) المحدد يساوي [BiLevel](../../com.aspose.slides/bilevel) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```


يحصل على بيانات تأثير Bi-Level الفعلية مع تطبيق الوراثة.

**الإرجاع:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - A [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان [BiLevel](../../com.aspose.slides/bilevel) المحدد يساوي [BiLevel](../../com.aspose.slides/bilevel) الحالي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | ال[BiLevel](../../com.aspose.slides/bilevel) للمقارنة. |

**الإرجاع:**
boolean - صحيح إذا كانت الكائنات متساوية؛ وإلا خطأ.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعمل كدالة تجزئة لنوع معين.

**الإرجاع:**
int - رمز تجزئة للكائن الحالي.