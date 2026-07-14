---
title: Blur
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل تأثير تمويه يتم تطبيقه على الشكل بالكامل بما في ذلك التعبئة.
type: docs
url: /ar/com.aspose.slides/blur/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

يمثل تأثير تمويه يُطبق على الشكل بالكامل، بما في ذلك التعبئة. جميع قنوات اللون، بما في ذلك ألفا، تتأثر.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getRadius()](#getRadius--) | يرجع أو يضبط نصف قطر التمويه. |
| [setRadius(double value)](#setRadius-double-) | يرجع أو يضبط نصف قطر التمويه. |
| [getGrow()](#getGrow--) | يحدد ما إذا كان ينبغي توسيع حدود الكائن نتيجةً للتمويه. |
| [setGrow(boolean value)](#setGrow-boolean-) | يحدد ما إذا كان ينبغي توسيع حدود الكائن نتيجةً للتمويه. |
| [getEffective()](#getEffective--) | يحصل على بيانات تأثير التمويه الفعّالة مع تطبيق الوراثة. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الـ [Blur](../../com.aspose.slides/blur) المحدد يساوي الـ [Blur](../../com.aspose.slides/blur) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئ (hash) لنوعٍ معين. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

يرجع أو يضبط نصف قطر التمويه. قراءة/كتابة double.

**الإرجاع:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

يرجع أو يضبط نصف قطر التمويه. قراءة/كتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

يحدد ما إذا كان ينبغي توسيع حدود الكائن نتيجةً للتمويه. True يشير إلى أن الحدود تُنْمَى بينما false يشير إلى أنها لا تُنْمَى. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

يحدد ما إذا كان ينبغي توسيع حدود الكائن نتيجةً للتمويه. True يشير إلى أن الحدود تُنْمَى بينما false يشير إلى أنها لا تُنْمَى. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

يحصل على بيانات تأثير التمويه الفعّالة مع تطبيق الوراثة.

**الإرجاع:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - A [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدد ما إذا كان الـ [Blur](../../com.aspose.slides/blur) المحدد يساوي الـ [Blur](../../com.aspose.slides/blur) الحالي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الـ [Blur](../../com.aspose.slides/blur) للمقارنة. |

**الإرجاع:**
boolean - true إذا كانت الكائنات متساوية؛ وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئ (hash) لنوعٍ معين.

**الإرجاع:**
int - رمز تجزئ (hash) للكائن الحالي.