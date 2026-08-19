---
title: Column
second_title: Aspose.Slides برای Java مرجع API
description: نمایانگر یک ستون در جدول است.
type: docs
url: /fa/com.aspose.slides/column/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

نمایانگر یک ستون در جدول است.
## متدها

| روش | توضیح |
| --- | --- |
| [getWidth()](#getWidth--) | عرض یک ستون را برمی‌گرداند یا تنظیم می‌کند. |
| [setWidth(double value)](#setWidth-double-) | عرض یک ستون را برمی‌گرداند یا تنظیم می‌کند. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | ویژگی‌های قالب‌بندی بخش تعریف‌شده را برای تمام بخش‌های سلول‌های ستون تنظیم می‌کند. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده را برای تمام پاراگراف‌های سلول‌های ستون تنظیم می‌کند. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | ویژگی‌های قالب‌بندی فریم متن تعریف‌شده را برای تمام فریم‌های متنی سلول‌های ستون تنظیم می‌کند. |
| [getColumnFormat()](#getColumnFormat--) | شیء ColumnFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی این ستون است. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```


عرض یک ستون را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**برگشت:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


عرض یک ستون را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


ویژگی‌های قالب‌بندی بخش تعریف‌شده را برای تمام بخش‌های سلول‌های ستون تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | شیء IPortionFormat که ویژگی‌های لازم تنظیم شده‌اند. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده را برای تمام پاراگراف‌های سلول‌های ستون تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | شیء IParagraphFormat که ویژگی‌های لازم تنظیم شده‌اند. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


ویژگی‌های قالب‌بندی فریم متنی تعریف‌شده را برای تمام فریم‌های متنی سلول‌های ستون تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | شیء ITextFrameFormat که ویژگی‌های لازم تنظیم شده‌اند. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```


شیء ColumnFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی این ستون است. فقط‌خواندنی [IColumnFormat](../../com.aspose.slides/icolumnformat).

**برگشت:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)