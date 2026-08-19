---
title: ITable
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک جدول بر روی اسلاید.
type: docs
url: /fa/com.aspose.slides/itable/
---
**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)  
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

نمایش‌دهنده یک جدول بر روی اسلاید.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | سلولی را که در ستون و ردیف مشخص‌شده قرار دارد باز می‌گرداند. |
| [getRows()](#getRows--) | مجموعه‌ای از ردیف‌ها را باز می‌گرداند. |
| [getColumns()](#getColumns--) | مجموعه‌ای از ستون‌ها را باز می‌گرداند. |
| [getTableFormat()](#getTableFormat--) | شیء TableFormat را که شامل ویژگی‌های قالب‌بندی برای این جدول است باز می‌گرداند. |
| [getStylePreset()](#getStylePreset--) | سبک جدول پیش‌ساخته را دریافت یا تنظیم می‌کند. |
| [setStylePreset(int value)](#setStylePreset-int-) | سبک جدول پیش‌ساخته را دریافت یا تنظیم می‌کند. |
| [getRightToLeft()](#getRightToLeft--) | تعیین می‌کند که آیا جدول ترتیب خواندن راست به چپ دارد یا نه. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | تعیین می‌کند که آیا جدول ترتیب خواندن راست به چپ دارد یا نه. |
| [getFirstRow()](#getFirstRow--) | تعیین می‌کند که آیا ردیف اول یک جدول باید با قالب‌بندی خاص رسم شود یا نه. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | تعیین می‌کند که آیا ردیف اول یک جدول باید با قالب‌بندی خاص رسم شود یا نه. |
| [getFirstCol()](#getFirstCol--) | تعیین می‌کند که آیا ستون اول یک جدول باید با قالب‌بندی خاص رسم شود یا نه. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | تعیین می‌کند که آیا ستون اول یک جدول باید با قالب‌بندی خاص رسم شود یا نه. |
| [getLastRow()](#getLastRow--) | تعیین می‌کند که آیا ردیف آخر یک جدول باید با قالب‌بندی خاص رسم شود یا نه. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | تعیین می‌کند که آیا ردیف آخر یک جدول باید با قالب‌بندی خاص رسم شود یا نه. |
| [getLastCol()](#getLastCol--) | تعیین می‌کند که آیا ستون آخر یک جدول باید با قالب‌بندی خاص رسم شود یا نه. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | تعیین می‌کند که آیا ستون آخر یک جدول باید با قالب‌بندی خاص رسم شود یا نه. |
| [getHorizontalBanding()](#getHorizontalBanding--) | تعیین می‌کند که آیا ردیف‌های زوج باید با قالب‌بندی متفاوت رسم شوند. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | تعیین می‌کند که آیا ردیف‌های زوج باید با قالب‌بندی متفاوت رسم شوند. |
| [getVerticalBanding()](#getVerticalBanding--) | تعیین می‌کند که آیا ستون‌های زوج باید با قالب‌بندی متفاوت رسم شوند. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | تعیین می‌کند که آیا ستون‌های زوج باید با قالب‌بندی متفاوت رسم شوند. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | سلول‌های همسایه را ادغام می‌کند. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

سلولی را که در ستون و ردیف مشخص‌شده قرار دارد باز می‌گرداند. فقط-خواندنی [ICell](../../com.aspose.slides/icell).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**بازگشت:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

مجموعه‌ای از ردیف‌ها را باز می‌گرداند. فقط-خواندنی [IRowCollection](../../com.aspose.slides/irowcollection).

**بازگشت:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

مجموعه‌ای از ستون‌ها را باز می‌گرداند. فقط-خواندنی [IColumnCollection](../../com.aspose.slides/icolumncollection).

**بازگشت:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

شیء TableFormat را که شامل ویژگی‌های قالب‌بندی برای این جدول است باز می‌گرداند. فقط-خواندنی [ITableFormat](../../com.aspose.slides/itableformat).

**بازگشت:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

سبک جدول پیش‌ساخته را دریافت یا تنظیم می‌کند. خواند و نوشت [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**بازگشت:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

سبک جدول پیش‌ساخته را دریافت یا تنظیم می‌کند. خواند و نوشت [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

تعیین می‌کند که آیا جدول ترتیب خواندن راست به چپ دارد یا نه. بولین قابل خواندن و نوشتن.

**بازگشت:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

تعیین می‌کند که آیا جدول ترتیب خواندن راست به چپ دارد یا نه. بولین قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

تعیین می‌کند که آیا ردیف اول یک جدول باید با قالب‌بندی خاص رسم شود یا نه. بولین قابل خواندن و نوشتن.

**بازگشت:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

تعیین می‌کند که آیا ردیف اول یک جدول باید با قالب‌بندی خاص رسم شود یا نه. بولین قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

تعیین می‌کند که آیا ستون اول یک جدول باید با قالب‌بندی خاص رسم شود یا نه. بولین قابل خواندن و نوشتن.

**بازگشت:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

تعیین می‌کند که آیا ستون اول یک جدول باید با قالب‌بندی خاص رسم شود یا نه. بولین قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

تعیین می‌کند که آیا ردیف آخر یک جدول باید با قالب‌بندی خاص رسم شود یا نه. بولین قابل خواندن و نوشتن.

**بازگشت:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

تعیین می‌کند که آیا ردیف آخر یک جدول باید با قالب‌بندی خاص رسم شود یا نه. بولین قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

تعیین می‌کند که آیا ستون آخر یک جدول باید با قالب‌بندی خاص رسم شود یا نه. بولین قابل خواندن و نوشتن.

**بازگشت:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

تعیین می‌کند که آیا ستون آخر یک جدول باید با قالب‌بندی خاص رسم شود یا نه. بولین قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

تعیین می‌کند که آیا ردیف‌های زوج باید با قالب‌بندی متفاوت رسم شوند. بولین قابل خواندن و نوشتن.

**بازگشت:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

تعیین می‌کند که آیا ردیف‌های زوج باید با قالب‌بندی متفاوت رسم شوند. بولین قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

تعیین می‌کند که آیا ستون‌های زوج باید با قالب‌بندی متفاوت رسم شوند. بولین قابل خواندن و نوشتن.

**بازگشت:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

تعیین می‌کند که آیا ستون‌های زوج باید با قالب‌بندی متفاوت رسم شوند. بولین قابل خواندن و نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

سلول‌های همسایه را ادغام می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | سلول برای ادغام. |
| cell2 | [ICell](../../com.aspose.slides/icell) | سلول برای ادغام. |
| allowSplitting | boolean | درست برای اجازه تقسیم سلول‌ها. |

**بازگشت:**
[ICell](../../com.aspose.slides/icell) - سلول ادغام‌شده.