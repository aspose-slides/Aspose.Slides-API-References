---
title: ILineFormatEffectiveData
second_title: مرجع API Aspose.Slides برای جاوا
description: شیء غیرقابل تغییر که ویژگی‌های قالب‌بندی خط مؤثر را شامل می‌شود.
type: docs
url: /fa/com.aspose.slides/ilineformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

شیء غیرقابل تغییر که ویژگی‌های قالب‌بندی خط مؤثر را شامل می‌شود.

--------------------

این رابط همراه با رابط [ILineFormat](../../com.aspose.slides/ilineformat) برای بازگرداندن مقادیر قالب‌بندی مؤثر با ارث‌برداری استفاده می‌شود.
## Methods

| Method | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | قالب پر شدن یک خط را برمی‌گرداند. |
| [getSketchFormat()](#getSketchFormat--) | قالب اسکچ یک خط را برمی‌گرداند. |
| [getWidth()](#getWidth--) | عرض یک خط را برمی‌گرداند. |
| [getDashStyle()](#getDashStyle--) | سبک خط تیره را برمی‌گرداند. |
| [getCustomDashPattern()](#getCustomDashPattern--) | الگوی خط تیره سفارشی را برمی‌گرداند. |
| [getCapStyle()](#getCapStyle--) | سبک سر انتهای خط را برمی‌گرداند. |
| [getStyle()](#getStyle--) | سبک خط را برمی‌گرداند. |
| [getAlignment()](#getAlignment--) | تراز خط را برمی‌گرداند. |
| [getJoinStyle()](#getJoinStyle--) | سبک اتصال خطوط را برمی‌گرداند. |
| [getMiterLimit()](#getMiterLimit--) | محدودیت میتر یک خط را برمی‌گرداند. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | سبک سر پیکان در ابتدای خط را برمی‌گرداند. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | سبک سر پیکان در پایان خط را برمی‌گرداند. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | عرض سر پیکان در ابتدای خط را برمی‌گرداند. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | عرض سر پیکان در پایان خط را برمی‌گرداند. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | طول سر پیکان در ابتدای خط را برمی‌گرداند. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | طول سر پیکان در پایان خط را برمی‌گرداند. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | تعیین می‌کند آیا دو نمونه ILineFormatEffectiveData برابر هستند یا خیر. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```


قالب پر شدن یک خط را برمی‌گرداند. فقط‌خواندنی [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**Returns:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```


قالب اسکچ یک خط را برمی‌گرداند. فقط‌خواندنی [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**Returns:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


عرض یک خط را برمی‌گرداند. فقط‌خواندنی double.

**Returns:**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


سبک خط تیره را برمی‌گرداند. فقط‌خواندنی [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Returns:**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


الگوی خط تیره سفارشی را برمی‌گرداند. فقط‌خواندنی float[].

**Returns:**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


سبک سر انتهای خط را برمی‌گرداند. فقط‌خواندنی [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Returns:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


سبک خط را برمی‌گرداند. فقط‌خواندنی [LineStyle](../../com.aspose.slides/linestyle).

**Returns:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


تراز خط را برمی‌گرداند. فقط‌خواندنی [LineAlignment](../../com.aspose.slides/linealignment).

**Returns:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


سبک اتصال خطوط را برمی‌گرداند. فقط‌خواندنی [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Returns:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


محدودیت میتر یک خط را برمی‌گرداند. فقط‌خواندنی float.

**Returns:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


سبک سر پیکان در ابتدای خط را برمی‌گرداند. فقط‌خواندنی [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Returns:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


سبک سر پیکان در پایان خط را برمی‌گرداند. فقط‌خواندنی [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Returns:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


عرض سر پیکان در ابتدای خط را برمی‌گرداند. فقط‌خواندنی [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Returns:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


عرض سر پیکان در پایان خط را برمی‌گرداند. فقط‌خواندنی [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Returns:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


طول سر پیکان در ابتدای خط را برمی‌گرداند. فقط‌خواندنی [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Returns:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


طول سر پیکان در پایان خط را برمی‌گرداند. فقط‌خواندنی [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Returns:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```


تعیین می‌کند آیا دو نمونه ILineFormatEffectiveData برابر هستند یا خیر.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | ILineFormatEffectiveData که با ILineFormatEffectiveData فعلی مقایسه می‌شود. |

**Returns:**
boolean - **true** اگر ILineFormatEffectiveData مشخص شده برابر با ILineFormatEffectiveData فعلی باشد؛ در غیر اینصورت، **false**.