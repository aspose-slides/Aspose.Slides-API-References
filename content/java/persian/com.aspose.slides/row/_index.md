---
title: Row
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک ردیف در جدول.
type: docs
url: /fa/com.aspose.slides/row/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**All Implemented Interfaces:**  
[com.aspose.slides.IRow](../../com.aspose.slides/irow)  
```
public final class Row extends CellCollection implements IRow
```

نمایانگر یک ردیف در جدول.

## متدها

| متد | توضیح |
| --- | --- |
| [getHeight()](#getHeight--) | ارتفاع یک ردیف را برمی‌گرداند. |
| [getMinimalHeight()](#getMinimalHeight--) | ارتفاع حداقل ممکن یک ردیف را برمی‌گرداند یا تنظیم می‌کند. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | ارتفاع حداقل ممکن یک ردیف را برمی‌گرداند یا تنظیم می‌کند. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | ویژگی‌های قالب‌بندی بخش تعریف‌شده را برای تمام بخش‌های سلول‌های ردیف تنظیم می‌کند. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده را برای تمام پاراگراف‌های سلول‌های ردیف تنظیم می‌کند. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | ویژگی‌های قالب‌بندی فریم متن تعریف‌شده را برای تمام فریم‌های متن سلول‌های ردیف تنظیم می‌کند. |
| [getRowFormat()](#getRowFormat--) | شیء RowFormat را که شامل ویژگی‌های قالب‌بندی برای این ردیف است برمی‌گرداند. |

### getHeight() {#getHeight--}
```
public final double getHeight()
```

ارتفاع یک ردیف را برمی‌گرداند. فقط خواندنی double.

**مقدار بازگشتی:**  
double

### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

ارتفاع حداقل ممکن یک ردیف را برمی‌گرداند یا تنظیم می‌کند. قابل نوشتن و خواندن double.

**مقدار بازگشتی:**  
double

### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

ارتفاع حداقل ممکن یک ردیف را برمی‌گرداند یا تنظیم می‌کند. قابل نوشتن و خواندن double.

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
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده را برای تمام پاراگراف‌های سلول‌های ردیف تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) |  |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

ویژگی‌های قالب‌بندی فریم متن تعریف‌شده را برای تمام فریم‌های متن سلول‌های ردیف تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) |  |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

شیء RowFormat را که شامل ویژگی‌های قالب‌بندی برای این ردیف است برمی‌گرداند. فقط خواندنی [IRowFormat](../../com.aspose.slides/irowformat).

**مقدار بازگشتی:**  
[IRowFormat](../../com.aspose.slides/irowformat)