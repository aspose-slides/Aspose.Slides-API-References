---
title: ILineFormatEffectiveData
second_title: مرجع API لـ Aspose.Slides for Java
description: كائن غير قابل للتغيير يحتوي على خصائص تنسيق الخط الفعّال.
type: docs
url: /ar/com.aspose.slides/ilineformateffectivedata/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

كائن غير قابل للتغيير يحتوي على خصائص تنسيق الخط الفعّال.

--------------------

يُستخدم هذا الواجهة مع الواجهة [ILineFormat](../../com.aspose.slides/ilineformat) لإرجاع قيم التنسيق الفعّال مع تطبيق الوراثة.
## الطرق

| Method | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | إرجاع تنسيق ملء الخط. |
| [getSketchFormat()](#getSketchFormat--) | إرجاع تنسيق الرسم التخطيطي للخط. |
| [getWidth()](#getWidth--) | إرجاع عرض الخط. |
| [getDashStyle()](#getDashStyle--) | إرجاع نمط الشرطة للخط. |
| [getCustomDashPattern()](#getCustomDashPattern--) | إرجاع نمط الشرطة المخصص. |
| [getCapStyle()](#getCapStyle--) | إرجاع نمط طرف الخط. |
| [getStyle()](#getStyle--) | إرجاع نمط الخط. |
| [getAlignment()](#getAlignment--) | إرجاع محاذاة الخط. |
| [getJoinStyle()](#getJoinStyle--) | إرجاع نمط تقاطع الخطوط. |
| [getMiterLimit()](#getMiterLimit--) | إرجاع حد الزاوية للخط. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | إرجاع نمط رأس السهم في بداية الخط. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | إرجاع نمط رأس السهم في نهاية الخط. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | إرجاع عرض رأس السهم في بداية الخط. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | إرجاع عرض رأس السهم في نهاية الخط. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | إرجاع طول رأس السهم في بداية الخط. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | إرجاع طول رأس السهم في نهاية الخط. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | تحديد ما إذا كان مثالي ILineFormatEffectiveData متساويين. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```


إرجاع تنسيق ملء الخط. للقراءة فقط [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**القيم المرجعة:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```


إرجاع تنسيق الرسم التخطيطي للخط. للقراءة فقط [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**القيم المرجعة:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


إرجاع عرض الخط. للقراءة فقط double.

**القيم المرجعة:**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


إرجاع نمط الشرطة للخط. للقراءة فقط [LineDashStyle](../../com.aspose.slides/linedashstyle).

**القيم المرجعة:**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


إرجاع نمط الشرطة المخصص. للقراءة فقط float[].

**القيم المرجعة:**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


إرجاع نمط طرف الخط. للقراءة فقط [LineCapStyle](../../com.aspose.slides/linecapstyle).

**القيم المرجعة:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


إرجاع نمط الخط. للقراءة فقط [LineStyle](../../com.aspose.slides/linestyle).

**القيم المرجعة:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


إرجاع محاذاة الخط. للقراءة فقط [LineAlignment](../../com.aspose.slides/linealignment).

**القيم المرجعة:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


إرجاع نمط تقاطع الخطوط. للقراءة فقط [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**القيم المرجعة:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


إرجاع حد الزاوية للخط. للقراءة فقط float.

**القيم المرجعة:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


إرجاع نمط رأس السهم في بداية الخط. للقراءة فقط [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**القيم المرجعة:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


إرجاع نمط رأس السهم في نهاية الخط. للقراءة فقط [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**القيم المرجعة:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


إرجاع عرض رأس السهم في بداية الخط. للقراءة فقط [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**القيم المرجعة:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


إرجاع عرض رأس السهم في نهاية الخط. للقراءة فقط [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**القيم المرجعة:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


إرجاع طول رأس السهم في بداية الخط. للقراءة فقط [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**القيم المرجعة:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


إرجاع طول رأس السهم في نهاية الخط. للقراءة فقط [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**القيم المرجعة:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```


تحديد ما إذا كان مثالي ILineFormatEffectiveData متساويين.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | مثيل ILineFormatEffectiveData للمقارنة مع مثيل ILineFormatEffectiveData الحالي. |

**القيم المرجعة:**
boolean - **true** إذا كان ILineFormatEffectiveData المحدد مساويًا لـ ILineFormatEffectiveData الحالي؛ وإلا **false**.