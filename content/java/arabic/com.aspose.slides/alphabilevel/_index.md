---
title: AlphaBiLevel
second_title: مرجع Aspose.Slides للغة Java
description: يمثل تأثير Alpha Bi-Level.
type: docs
url: /ar/com.aspose.slides/alphabilevel/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

يمثل تأثير Alpha Bi-Level. يتم تغيير قيم Alpha (العتامة) الأقل من العتبة إلى 0 (شفافية تماماً) والقيم الأكبر من أو تساوي العتبة إلى 100٪ (تغطية كاملة).
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getThreshold()](#getThreshold--) | يُرجع عتبة التأثير. |
| [setThreshold(float value)](#setThreshold-float-) | يُرجع عتبة التأثير. |
| [getEffective()](#getEffective--) | يحصل على بيانات تأثير Alpha Bi-Level الفعّالة مع تطبيق الوراثة. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدّد ما إذا كان [AlphaBiLevel](../../com.aspose.slides/alphabilevel) المحدد يساوي [AlphaBiLevel](../../com.aspose.slides/alphabilevel) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```


يُرجع عتبة التأثير. قراءة/كتابة float.

**القيمة المرجعة:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```


يُرجع عتبة التأثير. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```


يحصل على بيانات تأثير Alpha Bi-Level الفعّالة مع تطبيق الوراثة.

**القيمة المرجعة:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - كائن [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدّد ما إذا كان [AlphaBiLevel](../../com.aspose.slides/alphabilevel) المحدد يساوي [AlphaBiLevel](../../com.aspose.slides/alphabilevel) الحالي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaBiLevel](../../com.aspose.slides/alphabilevel) للمقارنة. |

**القيمة المرجعة:**
boolean - true إذا كانت الكائنات متساوية؛ وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعمل كدالة تجزئة لنوع معين.

**القيمة المرجعة:**
int - رمز تجزئة للكائن الحالي.