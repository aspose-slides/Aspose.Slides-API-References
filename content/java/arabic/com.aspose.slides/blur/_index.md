---
title: Blur
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل تأثير ضبابية يُطبّق على الشكل بأكمله بما في ذلك تعبئته.
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

يمثل تأثير ضبابية يُطبّق على الشكل بأكمله، بما في ذلك تعبئته. جميع قنوات اللون، بما في ذلك قناة ألفا، تتأثر.

## الطرق

| Method | Description |
| --- | --- |
| [getRadius()](#getRadius--) | إرجاع أو تعيين نصف قطر الضبابية. |
| [setRadius(double value)](#setRadius-double-) | إرجاع أو تعيين نصف قطر الضبابية. |
| [getGrow()](#getGrow--) | يحدد ما إذا كان ينبغي توسيع حدود الكائن نتيجة للضبابية. |
| [setGrow(boolean value)](#setGrow-boolean-) | يحدد ما إذا كان ينبغي توسيع حدود الكائن نتيجة للضبابية. |
| [getEffective()](#getEffective--) | يحصل على بيانات تأثير الضباب الفعّالة مع تطبيق الوراثة. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان [Blur](../../com.aspose.slides/blur) المحدد يساوي [Blur](../../com.aspose.slides/blur) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين. |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

إرجاع أو تعيين نصف قطر الضبابية. قراءة/كتابة من نوع double.

**الإرجاع:**  
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

إرجاع أو تعيين نصف قطر الضبابية. قراءة/كتابة من نوع double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

يحدد ما إذا كان ينبغي توسيع حدود الكائن نتيجة للضبابية. القيمة true تعني أن الحدود تُوسع، بينما false تعني عدم ذلك. قراءة/كتابة من نوع boolean.

**الإرجاع:**  
boolean

### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

يحدد ما إذا كان ينبغي توسيع حدود الكائن نتيجة للضبابية. القيمة true تعني أن الحدود تُوسع، بينما false تعني عدم ذلك. قراءة/كتابة من نوع boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

يحصل على بيانات تأثير الضباب الفعّالة مع تطبيق الوراثة.

**الإرجاع:**  
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - A [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدد ما إذا كان [Blur](../../com.aspose.slides/blur) المحدد يساوي [Blur](../../com.aspose.slides/blur) الحالي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | The [Blur](../../com.aspose.slides/blur) to compare. |

**الإرجاع:**  
boolean - true إذا كان الكائنان متساويين؛ وإلا false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين.

**الإرجاع:**  
int - رمز تجزئة للكائن الحالي.