---
title: IRow
second_title: مرجع API برای Aspose.Slides در Java
description: یک ردیف در جدول را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/irow/
---
**تمام اینترفیس‌های پیاده‌سازی شده:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

یک ردیف در جدول را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getHeight()](#getHeight--) | Returns the height of a row. |
| [getMinimalHeight()](#getMinimalHeight--) | Returns or sets the minimal possible height of a row. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Returns or sets the minimal possible height of a row. |
| [getRowFormat()](#getRowFormat--) | Returns the RowFormat object that contains formatting properties for this row. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

باز می‌گردد: ارتفاع یک ردیف. فقط-خواندنی double.

**باز می‌گردد:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

باز می‌گردد یا تنظیم می‌کند حداقل ارتفاع ممکن یک ردیف. قابل-نوشتن double.

**باز می‌گردد:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```

باز می‌گردد یا تنظیم می‌کند حداقل ارتفاع ممکن یک ردیف. قابل-نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```

باز می‌گردد شیء RowFormat که ویژگی‌های قالب‌بندی این ردیف را شامل می‌شود. فقط-خواندنی [IRowFormat](../../com.aspose.slides/irowformat).

**باز می‌گردد:**
[IRowFormat](../../com.aspose.slides/irowformat)