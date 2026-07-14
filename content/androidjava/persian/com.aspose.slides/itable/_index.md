---
title: ITable
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر یک جدول بر روی اسلاید است.
type: docs
url: /fa/com.aspose.slides/itable/
---
**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

نمایش یک جدول در اسلاید.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | سلول را در شاخص‌های ستون و ردیف مشخص‌شده برمی‌گرداند. |
| [getRows()](#getRows--) | مجموعهٔ سطرها را برمی‌گرداند. |
| [getColumns()](#getColumns--) | مجموعهٔ ستون‌ها را برمی‌گرداند. |
| [getTableFormat()](#getTableFormat--) | شیء TableFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی این جدول است. |
| [getStylePreset()](#getStylePreset--) | سبک جدولی پیش‌ساخته را دریافت یا تنظیم می‌کند. |
| [setStylePreset(int value)](#setStylePreset-int-) | سبک جدولی پیش‌ساخته را دریافت یا تنظیم می‌کند. |
| [getRightToLeft()](#getRightToLeft--) | تعیین می‌کند آیا جدول ترتیب خواندن راست-به-چپ دارد یا خیر. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | تعیین می‌کند آیا جدول ترتیب خواندن راست-به-چپ دارد یا خیر. |
| [getFirstRow()](#getFirstRow--) | تعیین می‌کند آیا سطر نخست جدول باید با قالب‌بندی ویژه رسم شود یا خیر. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | تعیین می‌کند آیا سطر نخست جدول باید با قالب‌بندی ویژه رسم شود یا خیر. |
| [getFirstCol()](#getFirstCol--) | تعیین می‌کند آیا ستون نخست جدول باید با قالب‌بندی ویژه رسم شود یا خیر. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | تعیین می‌کند آیا ستون نخست جدول باید با قالب‌بندی ویژه رسم شود یا خیر. |
| [getLastRow()](#getLastRow--) | تعیین می‌کند آیا سطر آخر جدول باید با قالب‌بندی ویژه رسم شود یا خیر. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | تعیین می‌کند آیا سطر آخر جدول باید با قالب‌بندی ویژه رسم شود یا خیر. |
| [getLastCol()](#getLastCol--) | تعیین می‌کند آیا ستون آخر جدول باید با قالب‌بندی ویژه رسم شود یا خیر. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | تعیین می‌کند آیا ستون آخر جدول باید با قالب‌بندی ویژه رسم شود یا خیر. |
| [getHorizontalBanding()](#getHorizontalBanding--) | تعیین می‌کند آیا ردیف‌های زوج باید با قالب‌بندی متفاوت رسم شوند یا خیر. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | تعیین می‌کند آیا ردیف‌های زوج باید با قالب‌بندی متفاوت رسم شوند یا خیر. |
| [getVerticalBanding()](#getVerticalBanding--) | تعیین می‌کند آیا ستون‌های زوج باید با قالب‌بندی متفاوت رسم شوند یا خیر. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | تعیین می‌کند آیا ستون‌های زوج باید با قالب‌بندی متفاوت رسم شوند یا خیر. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | سلول‌های همسایه را ادغام می‌کند. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

سلول را در شاخص‌های ستون و ردیف مشخص‌شده برمی‌گرداند. فقط خواندنی [ICell](../../com.aspose.slides/icell).

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

مجموعهٔ سطرها را برمی‌گرداند. فقط خواندنی [IRowCollection](../../com.aspose.slides/irowcollection).

**بازگشت:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

مجموعهٔ ستون‌ها را برمی‌گرداند. فقط خواندنی [IColumnCollection](../../com.aspose.slides/icolumncollection).

**بازگشت:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

شیء TableFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی این جدول است. فقط خواندنی [ITableFormat](../../com.aspose.slides/itableformat).

**بازگشت:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

سبک جدولی پیش‌ساخته را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**بازگشت:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

سبک جدولی پیش‌ساخته را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

تعیین می‌کند آیا جدول ترتیب خواندن راست-به-چپ دارد یا خیر. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

تعیین می‌کند آیا جدول ترتیب خواندن راست-به-چپ دارد یا خیر. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

تعیین می‌کند آیا سطر نخست جدول باید با قالب‌بندی ویژه رسم شود یا خیر. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

تعیین می‌کند آیا سطر نخست جدول باید با قالب‌بندی ویژه رسم شود یا خیر. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

تعیین می‌کند آیا ستون نخست جدول باید با قالب‌بندی ویژه رسم شود یا خیر. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

تعیین می‌کند آیا ستون نخست جدول باید با قالب‌بندی ویژه رسم شود یا خیر. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

تعیین می‌کند آیا سطر آخر جدول باید با قالب‌بندی ویژه رسم شود یا خیر. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

تعیین می‌کند آیا سطر آخر جدول باید با قالب‌بندی ویژه رسم شود یا خیر. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

تعیین می‌کند آیا ستون آخر جدول باید با قالب‌بندی ویژه رسم شود یا خیر. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

تعیین می‌کند آیا ستون آخر جدول باید با قالب‌بندی ویژه رسم شود یا خیر. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

تعیین می‌کند آیا ردیف‌های زوج باید با قالب‌بندی متفاوت رسم شوند یا خیر. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

تعیین می‌کند آیا ردیف‌های زوج باید با قالب‌بندی متفاوت رسم شوند یا خیر. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

تعیین می‌کند آیا ستون‌های زوج باید با قالب‌بندی متفاوت رسم شوند یا خیر. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

تعیین می‌کند آیا ستون‌های زوج باید با قالب‌بندی متفاوت رسم شوند یا خیر. خواندنی/نوشتنی boolean.

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
| allowSplitting | boolean | true برای اجازه تقسیم سلول‌ها. |

**بازگشت:**
[ICell](../../com.aspose.slides/icell) - سلول ادغام‌شده.