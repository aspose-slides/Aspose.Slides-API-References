---
title: HSL
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل تأثير تدرج اللون/التشبع/الإضاءة.
type: docs
url: /ar/com.aspose.slides/hsl/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect
```
public final class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

يمثل تأثير تدرج اللون / التشبع / الإضاءة. يمكن تعديل كل من اللون، التشبع والإضاءة نسبةً إلى قيمتها الحالية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getEffective()](#getEffective--) | يحصل على بيانات تأثير تدرج اللون / التشبع / الإضاءة الفعّالة مع تطبيق الوراثة. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الـ [HSL](../../com.aspose.slides/hsl) المحدد يساوي الـ [HSL](../../com.aspose.slides/hsl) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين. |
### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```


يحصل على بيانات تأثير تدرج اللون / التشبع / الإضاءة الفعّالة مع تطبيق الوراثة.

**القيمة المرجعة:**
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - [IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان الـ [HSL](../../com.aspose.slides/hsl) المحدد يساوي الـ [HSL](../../com.aspose.slides/hsl) الحالي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | [HSL](../../com.aspose.slides/hsl) للمقارنة. |

**القيمة المرجعة:**
boolean - true إذا كانت الكائنات متساوية؛ وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعمل كدالة تجزئة لنوع معين.

**القيمة المرجعة:**
int - رمز تجزئة للكيان الحالي.