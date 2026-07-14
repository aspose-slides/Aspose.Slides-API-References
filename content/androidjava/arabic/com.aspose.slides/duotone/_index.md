--- 
title: Duotone
second_title: Aspose.Slides للـ Android عبر مرجع API للغة Java
description: يمثل تأثير Duotone.
type: docs
url: /ar/com.aspose.slides/duotone/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**جميع الواجهات المطبقة:**  
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect  
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

يمثل تأثير Duotone. لكل بكسل، يجمع Color1 و Color2 من خلال استيفاء خطي لتحديد اللون الجديد لهذا البكسل.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getColor1()](#getColor1--) | يرسل تنسيق اللون المستهدف للبكسلات الداكنة. |
| [getColor2()](#getColor2--) | يرسل تنسيق اللون المستهدف للبكسلات الفاتحة. |
| [getEffective()](#getEffective--) | يحصل على بيانات تأثير Duotone الفعّالة مع تطبيق الوراثة. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان [Duotone](../../com.aspose.slides/duotone) المحدد يساوي [Duotone](../../com.aspose.slides/duotone) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```

يرجع تنسيق اللون المستهدف للبكسلات الداكنة. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```

يرجع تنسيق اللون المستهدف للبكسلات الفاتحة. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```

يحصل على بيانات تأثير Duotone الفعّالة مع تطبيق الوراثة.

**الإرجاع:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. للقراءة فقط long.

**الإرجاع:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدد ما إذا كان [Duotone](../../com.aspose.slides/duotone) المحدد يساوي [Duotone](../../com.aspose.slides/duotone) الحالي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | The [Duotone](../../com.aspose.slides/duotone) to compare. |

**الإرجاع:**
boolean - صحيح إذا كانت الكائنات متساوية؛ وإلا غير صحيح.
### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين.

**الإرجاع:**
int - رمز تجزئة للكائن الحالي.