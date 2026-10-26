---
title: Duotone
second_title: مرجع API Aspose.Slides للغة Java
description: يمثل تأثيرًا ثنائي النغمة.
type: docs
url: /ar/com.aspose.slides/duotone/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

يمثل تأثيرًا ثنائي النغمة. لكل بكسل، يجمع بين Color1 و Color2 من خلال استيفاء خطي لتحديد اللون الجديد لهذا البكسل.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getColor1()](#getColor1--) | يرجع تنسيق اللون المستهدف للبيكسلات الداكنة. |
| [getColor2()](#getColor2--) | يرجع تنسيق اللون المستهدف للبيكسلات الفاتحة. |
| [getEffective()](#getEffective--) | يحصل على بيانات تأثير Duotone الفعّالة مع تطبيق الوراثة. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الـ [Duotone](../../com.aspose.slides/duotone) المحدد مساويًا للـ [Duotone](../../com.aspose.slides/duotone) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```

يرجع تنسيق اللون المستهدف للبيكسلات الداكنة. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**القيمة المرجعة:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```

يرجع تنسيق اللون المستهدف للبيكسلات الفاتحة. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**القيمة المرجعة:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```

يحصل على بيانات تأثير Duotone الفعّالة مع تطبيق الوراثة.

**القيمة المرجعة:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - عنصر [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. للقراءة فقط long.

**القيمة المرجعة:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدد ما إذا كان الـ [Duotone](../../com.aspose.slides/duotone) المحدد مساويًا للـ [Duotone](../../com.aspose.slides/duotone) الحالي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الـ [Duotone](../../com.aspose.slides/duotone) للمقارنة. |

**القيمة المرجعة:**
boolean - true إذا كانت الكائنات متساوية؛ وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين.

**القيمة المرجعة:**
int - رمز تجزئة للكائن الحالي.