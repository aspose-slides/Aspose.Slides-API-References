---
title: AlphaBiLevel
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل تأثير Alpha Bi-Level.
type: docs
url: /ar/com.aspose.slides/alphabilevel/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

يمثل تأثير Alpha Bi-Level. قيم Alpha (الشفافية) الأقل من العتبة تتغير إلى 0 (شفافة تمامًا) وقيم Alpha الأكبر من أو يساوي العتبة تتغير إلى 100 % (معتمة تمامًا).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getThreshold()](#getThreshold--) | إرجاع عتبة التأثير. |
| [setThreshold(float value)](#setThreshold-float-) | إرجاع عتبة التأثير. |
| [getEffective()](#getEffective--) | الحصول على بيانات تأثير Alpha Bi-Level الفعّالة مع تطبيق الوراثة. |
| [equals(Object obj)](#equals-java.lang.Object-) | تحديد ما إذا كان [AlphaBiLevel](../../com.aspose.slides/alphabilevel) المحدد مساويًا لـ [AlphaBiLevel](../../com.aspose.slides/alphabilevel) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

إرجاع عتبة التأثير. قراءة/كتابة float.

**الإرجاع:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

إرجاع عتبة التأثير. قراءة/كتابة float.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

الحصول على بيانات تأثير Alpha Bi-Level الفعّالة مع تطبيق الوراثة.

**الإرجاع:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تحديد ما إذا كان [AlphaBiLevel](../../com.aspose.slides/alphabilevel) المحدد مساويًا لـ [AlphaBiLevel](../../com.aspose.slides/alphabilevel) الحالي.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaBiLevel](../../com.aspose.slides/alphabilevel) للمقارنة. |

**الإرجاع:**
boolean - true إذا كانت الكائنات متساوية؛ وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين.

**الإرجاع:**
int - رمز تجزئة للكائن الحالي.