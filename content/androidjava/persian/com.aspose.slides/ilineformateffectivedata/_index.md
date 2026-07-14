---
title: ILineFormatEffectiveData
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: شیء غیرقابل تغییر که شامل خصوصیات قالب‌بندی خط مؤثر است.
type: docs
url: /fa/com.aspose.slides/ilineformateffectivedata/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

شیء غیرقابل تغییر که خصوصیات قالب‌بندی خط مؤثر را شامل می‌شود.

--------------------

این رابط همراه با رابط [ILineFormat](../../com.aspose.slides/ilineformat) برای برگرداندن مقادیر قالب‌بندی مؤثر با اعمال وراثت استفاده می‌شود.
## متدها

| Method | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | قالب پر شدن یک خط را برمی‌گرداند. |
| [getSketchFormat()](#getSketchFormat--) | قالب اسکچ یک خط را برمی‌گرداند. |
| [getWidth()](#getWidth--) | عرض یک خط را برمی‌گرداند. |
| [getDashStyle()](#getDashStyle--) | سبک خط تیره را برمی‌گرداند. |
| [getCustomDashPattern()](#getCustomDashPattern--) | الگوی دلخواه خط تیره را برمی‌گرداند. |
| [getCapStyle()](#getCapStyle--) | سبک سر انتهای خط را برمی‌گرداند. |
| [getStyle()](#getStyle--) | سبک خط را برمی‌گرداند. |
| [getAlignment()](#getAlignment--) | تراز خط را برمی‌گرداند. |
| [getJoinStyle()](#getJoinStyle--) | سبک اتصال خطوط را برمی‌گرداند. |
| [getMiterLimit()](#getMiterLimit--) | حد مِیتر یک خط را برمی‌گرداند. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | سبک سرپیکان در ابتدای خط را برمی‌گرداند. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | سبک سرپیکان در انتهای خط را برمی‌گرداند. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | عرض سرپیکان در ابتدای خط را برمی‌گرداند. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | عرض سرپیکان در انتهای خط را برمی‌گرداند. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | طول سرپیکان در ابتدای خط را برمی‌گرداند. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | طول سرپیکان در انتهای خط را برمی‌گرداند. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | تعیین می‌کند آیا دو نمونه ILineFormatEffectiveData برابر هستند یا خیر. |

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```

قالب پر شدن یک خط را برمی‌گرداند. فقط-خواندنی [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**بازگشت:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```

قالب اسکچ یک خط را برمی‌گرداند. فقط-خواندنی [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**بازگشت:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

عرض یک خط را برمی‌گرداند. فقط-خواندنی double.

**بازگشت:**
double

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

سبک خط تیره را برمی‌گرداند. فقط-خواندنی [LineDashStyle](../../com.aspose.slides/linedashstyle).

**بازگشت:**
byte

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

الگوی دلخواه خط تیره را برمی‌گرداند. فقط-خواندنی float[].

**بازگشت:**
float[]

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

سبک سر انتهای خط را برمی‌گرداند. فقط-خواندنی [LineCapStyle](../../com.aspose.slides/linecapstyle).

**بازگشت:**
byte

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

سبک خط را برمی‌گرداند. فقط-خواندنی [LineStyle](../../com.aspose.slides/linestyle).

**بازگشت:**
byte

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

تراز خط را برمی‌گرداند. فقط-خواندنی [LineAlignment](../../com.aspose.slides/linealignment).

**بازگشت:**
byte

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

سبک اتصال خطوط را برمی‌گرداند. فقط-خواندنی [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**بازگشت:**
byte

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

حد مِیتر یک خط را برمی‌گرداند. فقط-خواندنی float.

**بازگشت:**
float

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

سبک سرپیکان در ابتدای خط را برمی‌گرداند. فقط-خواندنی [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**بازگشت:**
byte

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

سبک سرپیکان در انتهای خط را برمی‌گرداند. فقط-خواندنی [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**بازگشت:**
byte

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

عرض سرپیکان در ابتدای خط را برمی‌گرداند. فقط-خواندنی [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**بازگشت:**
byte

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

عرض سرپیکان در انتهای خط را برمی‌گرداند. فقط-خواندنی [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**بازگشت:**
byte

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

طول سرپیکان در ابتدای خط را برمی‌گرداند. فقط-خواندنی [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**بازگشت:**
byte

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

طول سرپیکان در انتهای خط را برمی‌گرداند. فقط-خواندنی [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**بازگشت:**
byte

### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```

مشخص می‌کند آیا دو نمونه ILineFormatEffectiveData برابر هستند یا خیر.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | ILineFormatEffectiveData برای مقایسه با ILineFormatEffectiveData فعلی. |

**بازگشت:**
boolean - **true** اگر ILineFormatEffectiveData مشخص‌شده برابر با ILineFormatEffectiveData فعلی باشد؛ در غیر این صورت، **false**.