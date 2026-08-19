---
title: ILineFormat
second_title: Aspose.Slides برای Java مرجع API
description: نمایانگر قالب یک خط است.
type: docs
url: /fa/com.aspose.slides/ilineformat/
---
**تمام اینترفیس‌های پیاده‌سازی شده:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

نمایانگر قالب یک خط است.
## متدها

| متد | توضیح |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | درست (true) برمی‌گرداند اگر قالب خط تعریف نشده باشد (به‌عنوان تازه ایجاد شده، پیش‌فرض). |
| [getFillFormat()](#getFillFormat--) | قالب پر کردن یک خط را برمی‌گرداند. |
| [getSketchFormat()](#getSketchFormat--) | قالب طرح‌کشی یک خط را برمی‌گرداند. |
| [getWidth()](#getWidth--) | عرض یک خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setWidth(double value)](#setWidth-double-) | عرض یک خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getDashStyle()](#getDashStyle--) | شیوه نقطه‌گذاری خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | شیوه نقطه‌گذاری خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getCustomDashPattern()](#getCustomDashPattern--) | الگوی نقطه‌گذاری سفارشی را برمی‌گرداند یا تنظیم می‌کند. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | الگوی نقطه‌گذاری سفارشی را برمی‌گرداند یا تنظیم می‌کند. |
| [getCapStyle()](#getCapStyle--) | شیوه نوک‌گذاری خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | شیوه نوک‌گذاری خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getStyle()](#getStyle--) | شیوه خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setStyle(byte value)](#setStyle-byte-) | شیوه خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getAlignment()](#getAlignment--) | همترازی خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setAlignment(byte value)](#setAlignment-byte-) | همترازی خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getJoinStyle()](#getJoinStyle--) | شیوه پیوستن خطوط را برمی‌گرداند یا تنظیم می‌کند. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | شیوه پیوستن خطوط را برمی‌گرداند یا تنظیم می‌کند. |
| [getMiterLimit()](#getMiterLimit--) | حد افراست (miter) یک خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | حد افراست (miter) یک خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | شیوه سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | شیوه سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | شیوه سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | شیوه سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | عرض سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | عرض سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | عرض سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | عرض سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | طول سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | طول سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | طول سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | طول سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | تعیین می‌کند آیا دو نمونه LineFormat برابر هستند یا نه. |
| [getEffective()](#getEffective--) | داده‌های قالب‌گذاری مؤثر خط را با به‌کارگیری ارث‌بری دریافت می‌کند. |

### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

درست (true) برمی‌گرداند اگر قالب خط تعریف نشده باشد (به‌عنوان تازه ایجاد شده، پیش‌فرض). فقط خواندنی boolean.

**بازگرداندن:**
boolean

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

قالب پر کردن یک خط را برمی‌گرداند. فقط خواندنی [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**بازگرداندن:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

قالب طرح‌کشی یک خط را برمی‌گرداند. فقط خواندنی [ISketchFormat](../../com.aspose.slides/isketchformat).

**بازگرداندن:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

عرض یک خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن double.

**بازگرداندن:**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

عرض یک خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن double.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

شیوه نقطه‌گذاری خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineDashStyle](../../com.aspose.slides/linedashstyle).

**بازگرداندن:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

شیوه نقطه‌گذاری خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineDashStyle](../../com.aspose.slides/linedashstyle).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

الگوی نقطه‌گذاری سفارشی را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float[].

**بازگرداندن:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

الگوی نقطه‌گذاری سفارشی را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float[].

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

شیوه نوک‌گذاری خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineCapStyle](../../com.aspose.slides/linecapstyle).

**بازگرداندن:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

شیوه نوک‌گذاری خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineCapStyle](../../com.aspose.slides/linecapstyle).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

شیوه خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineStyle](../../com.aspose.slides/linestyle).

**بازگرداندن:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

شیوه خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineStyle](../../com.aspose.slides/linestyle).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

همترازی خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineAlignment](../../com.aspose.slides/linealignment).

**بازگرداندن:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

همترازی خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineAlignment](../../com.aspose.slides/linealignment).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

شیوه پیوستن خطوط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**بازگرداندن:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

شیوه پیوستن خطوط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

حد افراست (miter) یک خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float.

**بازگرداندن:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

حد افراست (miter) یک خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

شیوه سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**بازگرداندن:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

شیوه سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

شیوه سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**بازگرداندن:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

شیوه سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

عرض سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**بازگرداندن:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

عرض سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

عرض سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**بازگرداندن:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

عرض سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

طول سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**بازگرداندن:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

طول سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

طول سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**بازگرداندن:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

طول سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

تعیین می‌کند آیا دو نمونه LineFormat برابر هستند یا نه.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | LineFormat برای مقایسه با LineFormat فعلی. |

**بازگرداندن:**
boolean - **true** اگر LineFormat مشخص‌شده برابر LineFormat فعلی باشد؛ در غیر این صورت **false**.

### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

داده‌های قالب‌گذاری مؤثر خط را با به‌کارگیری ارث‌بری دریافت می‌کند.

**بازگرداندن:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - یک [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).