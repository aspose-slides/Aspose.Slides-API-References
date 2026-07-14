---
title: Column
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک ستون در جدول است.
type: docs
url: /fa/com.aspose.slides/column/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**All Implemented Interfaces:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

نمایانگر یک ستون در جدول است.
## متدها

| متد | توضیح |
| --- | --- |
| [getWidth()](#getWidth--) | مقدار عرض یک ستون را برمی‌گرداند یا تنظیم می‌کند. |
| [setWidth(double value)](#setWidth-double-) | مقدار عرض یک ستون را برمی‌گرداند یا تنظیم می‌کند. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | ویژگی‌های قالب‌بندی بخش تعریف‌شده را برای تمام بخش‌های سلول‌های ستون تعیین می‌کند. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده را برای تمام پاراگراف‌های سلول‌های ستون تعیین می‌کند. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | ویژگی‌های قالب‌بندی قاب متن تعریف‌شده را برای تمام قاب‌های متن سلول‌های ستون تعیین می‌کند. |
| [getColumnFormat()](#getColumnFormat--) | شیء ColumnFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی این ستون است. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```

مقدار عرض یک ستون را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**بازگشت:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

مقدار عرض یک ستون را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

ویژگی‌های قالب‌بندی بخش تعریف‌شده را برای تمام بخش‌های سلول‌های ستون تعیین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | شیء IPortionFormat با ویژگی‌های لازم تنظیم‌شده. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده را برای تمام پاراگراف‌های سلول‌های ستون تعیین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | شیء IParagraphFormat با ویژگی‌های لازم تنظیم‌شده. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

ویژگی‌های قالب‌بندی قاب متن تعریف‌شده را برای تمام قاب‌های متن سلول‌های ستون تعیین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | شیء ITextFrameFormat با ویژگی‌های لازم تنظیم‌شده. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```

شیء ColumnFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی این ستون است. فقط-خواندنی [IColumnFormat](../../com.aspose.slides/icolumnformat).

**بازگشت:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)