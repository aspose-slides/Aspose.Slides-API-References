---
title: ILineFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: قالب یک خط را نمایان می‌کند.
type: docs
url: /fa/com.aspose.slides/ilineformat/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

نمایانگر قالب یک خط است.
## متدها

| متد | توضیح |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | در صورت عدم تعریف قالب خط (به‌عنوان تازه ساخته‌شده، پیش‌فرض) مقدار true را باز می‌گرداند. |
| [getFillFormat()](#getFillFormat--) | قالب پر کردن یک خط را باز می‌گرداند. |
| [getSketchFormat()](#getSketchFormat--) | قالب طرح‌کش یک خط را باز می‌گرداند. |
| [getWidth()](#getWidth--) | عرض یک خط را باز می‌گرداند یا تنظیم می‌کند. |
| [setWidth(double value)](#setWidth-double-) | عرض یک خط را باز می‌گرداند یا تنظیم می‌کند. |
| [getDashStyle()](#getDashStyle--) | سبک خط چین خط را باز می‌گرداند یا تنظیم می‌کند. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | سبک خط چین خط را باز می‌گرداند یا تنظیم می‌کند. |
| [getCustomDashPattern()](#getCustomDashPattern--) | الگوی سفارشی خط چین را باز می‌گرداند یا تنظیم می‌کند. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Returns or sets the custom dash pattern. |
| [getCapStyle()](#getCapStyle--) | سبک سر انتهای خط را باز می‌گرداند یا تنظیم می‌کند. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | سبک سر انتهای خط را باز می‌گرداند یا تنظیم می‌کند. |
| [getStyle()](#getStyle--) | سبک خط را باز می‌گرداند یا تنظیم می‌کند. |
| [setStyle(byte value)](#setStyle-byte-) | سبک خط را باز می‌گرداند یا تنظیم می‌کند. |
| [getAlignment()](#getAlignment--) | ترازبندی خط را باز می‌گرداند یا تنظیم می‌کند. |
| [setAlignment(byte value)](#setAlignment-byte-) | ترازبندی خط را باز می‌گرداند یا تنظیم می‌کند. |
| [getJoinStyle()](#getJoinStyle--) | سبک پیوستگی خطوط را باز می‌گرداند یا تنظیم می‌کند. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | سبک پیوستگی خطوط را باز می‌گرداند یا تنظیم می‌کند. |
| [getMiterLimit()](#getMiterLimit--) | حداکثر مِیتر یک خط را باز می‌گرداند یا تنظیم می‌کند. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | حداکثر مِیتر یک خط را باز می‌گرداند یا تنظیم می‌کند. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | سبک سرپیکان در ابتدای یک خط را باز می‌گرداند یا تنظیم می‌کند. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | سبک سرپیکان در ابتدای یک خط را باز می‌گرداند یا تنظیم می‌کند. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | سبک سرپیکان در انتهای یک خط را باز می‌گرداند یا تنظیم می‌کند. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | سبک سرپیکان در انتهای یک خط را باز می‌گرداند یا تنظیم می‌کند. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | عرض سرپیکان در ابتدای یک خط را باز می‌گرداند یا تنظیم می‌کند. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | عرض سرپیکان در ابتدای یک خط را باز می‌گرداند یا تنظیم می‌کند. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | عرض سرپیکان در انتهای یک خط را باز می‌گرداند یا تنظیم می‌کند. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | عرض سرپیکان در انتهای یک خط را باز می‌گرداند یا تنظیم می‌کند. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | طول سرپیکان در ابتدای یک خط را باز می‌گرداند یا تنظیم می‌کند. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | طول سرپیکان در ابتدای یک خط را باز می‌گرداند یا تنظیم می‌کند. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | طول سرپیکان در انتهای یک خط را باز می‌گرداند یا تنظیم می‌کند. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | طول سرپیکان در انتهای یک خط را باز می‌گرداند یا تنظیم می‌کند. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | تعیین می‌کند آیا دو نمونه LineFormat برابر هستند یا خیر. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی مؤثر خط را با اعمال وراثت دریافت می‌کند. |
### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```


در صورت عدم تعریف قالب خط (به عنوان تازه ایجاد شده، پیش‌فرض) مقدار true را باز می‌گرداند. فقط‌خواندنی boolean.

**باز می‌گردد:**
boolean
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```


قالب پر کردن یک خط را باز می‌گرداند. فقط‌خواندنی [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**باز می‌گردد:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```


قالب طرح‌کش یک خط را باز می‌گرداند. فقط‌خواندنی [ISketchFormat](../../com.aspose.slides/isketchformat).

**باز می‌گردد:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


عرض یک خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن double.

**باز می‌گردد:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```


عرض یک خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


سبک خط چین خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineDashStyle](../../com.aspose.slides/linedashstyle).

**باز می‌گردد:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```


سبک خط چین خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineDashStyle](../../com.aspose.slides/linedashstyle).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


الگوی سفارشی خط چین را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن float[].

**باز می‌گردد:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```


الگوی سفارشی خط چین را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن float[].

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


سبک سر انتهای خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineCapStyle](../../com.aspose.slides/linecapstyle).

**باز می‌گردد:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```


سبک سر انتهای خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineCapStyle](../../com.aspose.slides/linecapstyle).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


سبک خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineStyle](../../com.aspose.slides/linestyle).

**باز می‌گردد:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```


سبک خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineStyle](../../com.aspose.slides/linestyle).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


ترازبندی خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineAlignment](../../com.aspose.slides/linealignment).

**باز می‌گردد:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```


ترازبندی خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineAlignment](../../com.aspose.slides/linealignment).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


سبک پیوستگی خطوط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**باز می‌گردد:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```


سبک پیوستگی خطوط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


حداکثر مِیتر یک خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن float.

**باز می‌گردد:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```


حداکثر مِیتر یک خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


سبک سرپیکان در ابتدای یک خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**باز می‌گردد:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```


سبک سرپیکان در ابتدای یک خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


سبک سرپیکان در انتهای یک خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**باز می‌گردد:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```


سبک سرپیکان در انتهای یک خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


عرض سرپیکان در ابتدای یک خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**باز می‌گردد:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```


عرض سرپیکان در ابتدای یک خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


عرض سرپیکان در انتهای یک خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**باز می‌گردد:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```


عرض سرپیکان در انتهای یک خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


طول سرپیکان در ابتدای یک خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**باز می‌گردد:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```


طول سرپیکان در ابتدای یک خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


طول سرپیکان در انتهای یک خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**باز می‌گردد:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```


طول سرپیکان در انتهای یک خط را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```


تعیین می‌کند آیا دو نمونه LineFormat برابر هستند یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | نمونه LineFormat برای مقایسه با نمونهٔ فعلی. |

**باز می‌گردد:**
boolean - **true** اگر LineFormat مشخص شده برابر با نمونهٔ فعلی باشد؛ در غیر این صورت **false**.
### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```


داده‌های قالب‌بندی مؤثر خط را با اعمال وراثت دریافت می‌کند.

**باز می‌گردد:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).