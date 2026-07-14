---
title: ILineFormatEffectiveData
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة Java
description: كائن غير قابل للتغيير يحتوي على خصائص تنسيق الخط الفعّال.
type: docs
url: /ar/com.aspose.slides/ilineformateffectivedata/
---
**جميع الواجهات المطبقة:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

كائن غير قابل للتغيير يحتوي على خصائص تنسيق الخط الفعّال.

--------------------

تُستخدم هذه الواجهة مع واجهة [ILineFormat](../../com.aspose.slides/ilineformat) لإرجاع قيم التنسيق الفعّال مع تطبيق الوراثة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | يعيد تنسيق تعبئة الخط. |
| [getSketchFormat()](#getSketchFormat--) | يعيد تنسيق الرسم التخطيطي للخط. |
| [getWidth()](#getWidth--) | يعيد عرض الخط. |
| [getDashStyle()](#getDashStyle--) | يعيد نمط الشرط للخط. |
| [getCustomDashPattern()](#getCustomDashPattern--) | يعيد نمط الشرط المخصص. |
| [getCapStyle()](#getCapStyle--) | يعيد نمط طرف الخط. |
| [getStyle()](#getStyle--) | يعيد نمط الخط. |
| [getAlignment()](#getAlignment--) | يعيد محاذاة الخط. |
| [getJoinStyle()](#getJoinStyle--) | يعيد نمط ربط الخطوط. |
| [getMiterLimit()](#getMiterLimit--) | يعيد حد التقاء الزوايا للخط. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | يعيد نمط رأس السهم في بداية الخط. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | يعيد نمط رأس السهم في نهاية الخط. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | يعيد عرض رأس السهم في بداية الخط. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | يعيد عرض رأس السهم في نهاية الخط. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | يعيد طول رأس السهم في بداية الخط. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | يعيد طول رأس السهم في نهاية الخط. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | يحدد ما إذا كانت مثيلتا ILineFormatEffectiveData متساويتين. |

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```

يعيد تنسيق تعبئة الخط. للقراءة فقط [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**الإرجاع:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```

يعيد تنسيق الرسم التخطيطي للخط. للقراءة فقط [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**الإرجاع:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

يعيد عرض الخط. للقراءة فقط double.

**الإرجاع:**
double

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

يعيد نمط الشرط للخط. للقراءة فقط [LineDashStyle](../../com.aspose.slides/linedashstyle).

**الإرجاع:**
byte

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

يعيد نمط الشرط المخصص. للقراءة فقط float[].

**الإرجاع:**
float[]

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

يعيد نمط طرف الخط. للقراءة فقط [LineCapStyle](../../com.aspose.slides/linecapstyle).

**الإرجاع:**
byte

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

يعيد نمط الخط. للقراءة فقط [LineStyle](../../com.aspose.slides/linestyle).

**الإرجاع:**
byte

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

يعيد محاذاة الخط. للقراءة فقط [LineAlignment](../../com.aspose.slides/linealignment).

**الإرجاع:**
byte

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

يعيد نمط ربط الخطوط. للقراءة فقط [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**الإرجاع:**
byte

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

يعيد حد التقاء الزوايا للخط. للقراءة فقط float.

**الإرجاع:**
float

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

يعيد نمط رأس السهم في بداية الخط. للقراءة فقط [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**الإرجاع:**
byte

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

يعيد نمط رأس السهم في نهاية الخط. للقراءة فقط [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**الإرجاع:**
byte

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

يعيد عرض رأس السهم في بداية الخط. للقراءة فقط [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**الإرجاع:**
byte

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

يعيد عرض رأس السهم في نهاية الخط. للقراءة فقط [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**الإرجاع:**
byte

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

يعيد طول رأس السهم في بداية الخط. للقراءة فقط [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**الإرجاع:**
byte

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

يعيد طول رأس السهم في نهاية الخط. للقراءة فقط [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**الإرجاع:**
byte

### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```

يحدد ما إذا كانت مثيلتا ILineFormatEffectiveData متساويتين.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | كائن ILineFormatEffectiveData للمقارنة مع ILineFormatEffectiveData الحالي. |

**الإرجاع:**
boolean - **true** إذا كان ILineFormatEffectiveData المحدد مساويًا لـ ILineFormatEffectiveData الحالي؛ وإلا **false**.