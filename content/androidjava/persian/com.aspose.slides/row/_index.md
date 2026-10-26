---
title: Row
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: یک ردیف در جدول را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/row/
---
**Inheritance:**  
ارث‌بری: java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**All Implemented Interfaces:**  
تمام واسط‌های پیاده‌سازی‌شده: [com.aspose.slides.IRow](../../com.aspose.slides/irow) ```
public final class Row extends CellCollection implements IRow
```

Represents a row in a table.  
یک ردیف در جدول را نمایش می‌دهد.

## متدها

| متد | توضیح |
| --- | --- |
| [getHeight()](#getHeight--) | ارتفاع یک ردیف را برمی‌گرداند. |
| [getMinimalHeight()](#getMinimalHeight--) | ارتفاع حداقل ممکن یک ردیف را برمی‌گرداند یا تنظیم می‌کند. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | ارتفاع حداقل ممکن یک ردیف را برمی‌گرداند یا تنظیم می‌کند. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | ویژگی‌های قالب‌بندی بخش تعریف‌شده را برای تمام بخش‌های سلول‌های ردیف تنظیم می‌کند. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده را برای تمام پاراگراف‌های سلول‌های ردیف تنظیم می‌کند. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | ویژگی‌های قالب‌بندی فریم متن تعریف‌شده را برای تمام فریم‌های متنی سلول‌های ردیف تنظیم می‌کند. |
| [getRowFormat()](#getRowFormat--) | شیء RowFormat را که شامل ویژگی‌های قالب‌بندی برای این ردیف است برمی‌گرداند. |

### getHeight() {#getHeight--}
```
public final double getHeight()
```

ارتفاع یک ردیف را برمی‌گرداند. فقط‌خواندنی double.

**بازگرداندن:**  
double

### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

ارتفاع حداقل ممکن یک ردیف را برمی‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی double.

**بازگرداندن:**  
double

### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

ارتفاع حداقل ممکن یک ردیف را برمی‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

ویژگی‌های قالب‌بندی بخش تعریف‌شده را برای تمام بخش‌های سلول‌های ردیف تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | شیء IPortionFormat با ویژگی‌های لازم تنظیم‌شده. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده را برای تمام پاراگراف‌های سلول‌های ردیف تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | شیء IParagraphFormat با ویژگی‌های لازم تنظیم‌شده. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

ویژگی‌های قالب‌بندی فریم متن تعریف‌شده را برای تمام فریم‌های متنی سلول‌های ردیف تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | شیء ITextFrameFormat با ویژگی‌های لازم تنظیم‌شده. |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

شیء RowFormat را که شامل ویژگی‌های قالب‌بندی برای این ردیف است برمی‌گرداند. فقط‌خواندنی [IRowFormat](../../com.aspose.slides/irowformat).

**بازگرداندن:**  
[IRowFormat](../../com.aspose.slides/irowformat)