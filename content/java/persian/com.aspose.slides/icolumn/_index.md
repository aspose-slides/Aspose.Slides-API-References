---
title: IColumn
second_title: مرجع API Aspose.Slides برای جاوا
description: ستونی در جدول را نمایندگی می‌کند.
type: docs
url: /fa/com.aspose.slides/icolumn/
---
**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)  
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

ستونی در جدول را نمایندگی می‌کند.

## متدها

| متد | توضیح |
| --- | --- |
| [getWidth()](#getWidth--) | عرض یک ستون را برمی‌گرداند یا تنظیم می‌کند. |
| [setWidth(double value)](#setWidth-double-) | عرض یک ستون را برمی‌گرداند یا تنظیم می‌کند. |
| [getColumnFormat()](#getColumnFormat--) | آبجکت ColumnFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی برای این ستون است. |

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

عرض یک ستون را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**باز می‌گردد:**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

عرض یک ستون را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

آبجکت ColumnFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی برای این ستون است. فقط-خواندنی [IColumnFormat](../../com.aspose.slides/icolumnformat).

**باز می‌گردد:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)