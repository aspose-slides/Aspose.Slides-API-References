---
title: IColumn
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک ستون در جدول است.
type: docs
url: /fa/com.aspose.slides/icolumn/
---
**All Implemented Interfaces:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

نمایانگر یک ستون در جدول.

## متدها

| متد | توضیح |
| --- | --- |
| [getWidth()](#getWidth--) | عرض یک ستون را برمی‌گرداند یا تنظیم می‌کند. |
| [setWidth(double value)](#setWidth-double-) | عرض یک ستون را برمی‌گرداند یا تنظیم می‌کند. |
| [getColumnFormat()](#getColumnFormat--) | شیء ColumnFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی برای این ستون است. |

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

عرض یک ستون را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**بازگشت:**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

عرض یک ستون را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

شیء ColumnFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی برای این ستون است. فقط‌خواندنی [IColumnFormat](../../com.aspose.slides/icolumnformat).

**بازگشت:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)