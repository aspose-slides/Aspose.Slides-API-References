---
title: LineFormat
second_title: مرجع API جاوا Aspose.Slides برای اندروید
description: قالب یک خط را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/lineformat/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

نمایش قالب یک خط.
## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | در صورتی که قالب خط تعریف نشده باشد (به‌عنوان تازه ایجاد شده، پیش‌فرض) true را برمی‌گرداند. |
| [getFillFormat()](#getFillFormat--) | قالب پر کردن یک خط را برمی‌گرداند. |
| [getSketchFormat()](#getSketchFormat--) | قالب اسکچ یک خط را برمی‌گرداند. |
| [getWidth()](#getWidth--) | عرض یک خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setWidth(double value)](#setWidth-double-) | عرض یک خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getDashStyle()](#getDashStyle--) | سبک خط نقطه‌دار را برمی‌گرداند یا تنظیم می‌کند. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | سبک خط نقطه‌دار را برمی‌گرداند یا تنظیم می‌کند. |
| [getCustomDashPattern()](#getCustomDashPattern--) | الگوی دلخواه نقطه‌دار را برمی‌گرداند یا تنظیم می‌کند. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | الگوی دلخواه نقطه‌دار را برمی‌گرداند یا تنظیم می‌کند. |
| [getCapStyle()](#getCapStyle--) | سبک انتهای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | سبک انتهای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getStyle()](#getStyle--) | سبک خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setStyle(byte value)](#setStyle-byte-) | سبک خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getAlignment()](#getAlignment--) | تراز خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setAlignment(byte value)](#setAlignment-byte-) | تراز خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getJoinStyle()](#getJoinStyle--) | سبک اتصال خطوط را برمی‌گرداند یا تنظیم می‌کند. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | سبک اتصال خطوط را برمی‌گرداند یا تنظیم می‌کند. |
| [getMiterLimit()](#getMiterLimit--) | حد میتر یک خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | حد میتر یک خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | سبک سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | سبک سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | سبک سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | سبک سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | عرض سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | عرض سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | عرض سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | عرض سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | طول سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | طول سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | طول سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | طول سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | تعیین می‌کند که آیا دو نمونه LineFormat برابر هستند یا خیر. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی مؤثر خط را با اعمال ارث‌بری دریافت می‌کند. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط-خواندنی long.

**بازمی‌گرداند:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

با شیء مشخص شده مقایسه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object |  |

**بازمی‌گرداند:**
boolean

### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

در صورتی که قالب خط تعریف نشده باشد (به‌عنوان تازه ایجاد شده، پیش‌فرض) true را برمی‌گرداند. فقط-خواندنی boolean .

**بازمی‌گرداند:**
boolean

### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

قالب پر کردن یک خط را برمی‌گرداند. فقط-خواندنی [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**بازمی‌گرداند:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

قالب اسکچ یک خط را برمی‌گرداند. فقط-خواندنی [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**بازمی‌گرداند:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public final double getWidth()
```

عرض یک خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن double .

**بازمی‌گرداند:**
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

عرض یک خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن double .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

سبک خط نقطه‌دار را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineDashStyle](../../com.aspose.slides/linedashstyle).

**بازمی‌گرداند:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

سبک خط نقطه‌دار را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineDashStyle](../../com.aspose.slides/linedashstyle).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

الگوی دلخواه نقطه‌دار را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float[] .

**بازمی‌گرداند:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

الگوی دلخواه نقطه‌دار را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float[] .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

سبک انتهای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineCapStyle](../../com.aspose.slides/linecapstyle).

**بازمی‌گرداند:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

سبک انتهای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineCapStyle](../../com.aspose.slides/linecapstyle).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public final byte getStyle()
```

سبک خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineStyle](../../com.aspose.slides/linestyle).

**بازمی‌گرداند:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

سبک خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineStyle](../../com.aspose.slides/linestyle).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

تراز خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineAlignment](../../com.aspose.slides/linealignment).

**بازمی‌گرداند:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

تراز خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineAlignment](../../com.aspose.slides/linealignment).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

سبک اتصال خطوط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**بازمی‌گرداند:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

سبک اتصال خطوط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

حد میتر یک خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float .

**بازمی‌گرداند:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

حد میتر یک خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

سبک سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**بازمی‌گرداند:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

سبک سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

سبک سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**بازمی‌گرداند:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

سبک سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

عرض سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**بازمی‌گرداند:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

عرض سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

عرض سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**بازمی‌گرداند:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

عرض سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

طول سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**بازمی‌گرداند:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

طول سرپیکان در ابتدای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

طول سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**بازمی‌گرداند:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

طول سرپیکان در انتهای خط را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

تعیین می‌کند که آیا دو نمونه LineFormat برابر هستند یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | The LineFormat to compare with the current LineFormat. |

**بازمی‌گرداند:**
boolean - **true** if the specified LineFormat is equal to the current LineFormat; otherwise, **false**.

### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

داده‌های قالب‌بندی مؤثر خط را با اعمال ارث‌بری دریافت می‌کند.

--------------------

> ```
> This example demonstrates getting shape's effective line format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	ILineFormatEffectiveData effectiveLineFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getLineFormat().getEffective();
>  	System.out.println("Style: " + effectiveLineFormat.getStyle());
>  	System.out.println("Width: " + effectiveLineFormat.getWidth());
>  	System.out.println("Fill type: " + effectiveLineFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گرداند:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - یک [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).