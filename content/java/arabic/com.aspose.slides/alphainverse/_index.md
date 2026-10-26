---
title: AlphaInverse
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل تأثير Alpha عكسي.
type: docs
url: /ar/com.aspose.slides/alphainverse/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

يمثل تأثير Alpha عكسي. يتم عكس قيم Alpha (الشفافية) بطرحها من 100%.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getEffective()](#getEffective--) | يحصل على بيانات تأثير Alpha العكسي الفعّال مع تطبيق الوراثة. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان [AlphaInverse](../../com.aspose.slides/alphainverse) المحدد يساوي [AlphaInverse](../../com.aspose.slides/alphainverse) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين. |

### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```

يحصل على بيانات تأثير Alpha العكسي الفعّال مع تطبيق الوراثة.

**القيمة المرجعة:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط long.

**القيمة المرجعة:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدد ما إذا كان [AlphaInverse](../../com.aspose.slides/alphainverse) المحدد يساوي [AlphaInverse](../../com.aspose.slides/alphainverse) الحالي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaInverse](../../com.aspose.slides/alphainverse) للمقارنة. |

**القيمة المرجعة:**
boolean - true إذا كانت الكائنات متساوية؛ وإلا false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين.

**القيمة المرجعة:**
int - رمز تجزئة للكائن الحالي.