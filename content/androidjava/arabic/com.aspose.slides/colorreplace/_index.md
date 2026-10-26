---
title: ColorReplace
second_title: Aspose.Slides للأندرويد عبر مرجع API لجافا
description: يمثل تأثير استبدال اللون.
type: docs
url: /ar/com.aspose.slides/colorreplace/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable  
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

يمثل تأثير استبدال اللون. يتم تغيير جميع ألوان التأثير إلى لون ثابت. قيم ألفا لا تتأثر.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getColor()](#getColor--) | إرجاع تنسيق اللون الذي سيستبدل لون كل بكسل. |
| [getEffective()](#getEffective--) | الحصول على بيانات تأثير استبدال اللون الفعلية مع تطبيق الوراثة. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | تحديد ما إذا كان [ColorReplace](../../com.aspose.slides/colorreplace) المحدد مساويًا للـ [ColorReplace](../../com.aspose.slides/colorreplace) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

إرجاع تنسيق اللون الذي سيستبدل لون كل بكسل. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**القيمة المرجعة:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

الحصول على بيانات تأثير استبدال اللون الفعلية مع تطبيق الوراثة.

**القيمة المرجعة:**  
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
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

تحديد ما إذا كان [ColorReplace](../../com.aspose.slides/colorreplace) المحدد مساويًا للـ [ColorReplace](../../com.aspose.slides/colorreplace) الحالي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الـ [ColorReplace](../../com.aspose.slides/colorreplace) للمقارنة. |

**القيمة المرجعة:**  
منطقي - true إذا كانت الكائنات متساوية؛ وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين.

**القيمة المرجعة:**  
int - رمز تجزئة للكائن الحالي.