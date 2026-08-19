---
title: Table
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایشی از یک جدول در یک اسلاید.
type: docs
url: /fa/com.aspose.slides/table/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

نمایشی از یک جدول در یک اسلاید.
## متدها

| Method | Description |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | سلول را در ستون و ردیف مشخص‌شده بر می‌گرداند. |
| [getRows()](#getRows--) | مجموعه سطرها را بر می‌گرداند. |
| [getColumns()](#getColumns--) | مجموعه ستون‌ها را بر می‌گرداند. |
| [getTableFormat()](#getTableFormat--) | شیء TableFormat را که شامل خواص قالب‌بندی برای این جدول است بر می‌گرداند. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | ادغام سلول‌های همجوار. |
| [getStylePreset()](#getStylePreset--) | دریافت یا تنظیم سبک جدول داخلی. |
| [setStylePreset(int value)](#setStylePreset-int-) | دریافت یا تنظیم سبک جدول داخلی. |
| [getRightToLeft()](#getRightToLeft--) | تعیین می‌کند که آیا جدول ترتیب خوانش راست به چپ دارد یا خیر. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | تعیین می‌کند که آیا جدول ترتیب خوانش راست به چپ دارد یا خیر. |
| [getFirstRow()](#getFirstRow--) | تعیین می‌کند که آیا ردیف اول جدول باید با قالب‌بندی ویژه‌ای رسم شود. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | تعیین می‌کند که آیا ردیف اول جدول باید با قالب‌بندی ویژه‌ای رسم شود. |
| [getFirstCol()](#getFirstCol--) | تعیین می‌کند که آیا ستون اول جدول باید با قالب‌بندی ویژه‌ای رسم شود. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | تعیین می‌کند که آیا ستون اول جدول باید با قالب‌بندی ویژه‌ای رسم شود. |
| [getLastRow()](#getLastRow--) | تعیین می‌کند که آیا آخرین ردیف جدول باید با قالب‌بندی ویژه‌ای رسم شود. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | تعیین می‌کند که آیا آخرین ردیف جدول باید با قالب‌بندی ویژه‌ای رسم شود. |
| [getLastCol()](#getLastCol--) | تعیین می‌کند که آیا آخرین ستون جدول باید با قالب‌بندی ویژه‌ای رسم شود. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | تعیین می‌کند که آیا آخرین ستون جدول باید با قالب‌بندی ویژه‌ای رسم شود. |
| [getHorizontalBanding()](#getHorizontalBanding--) | تعیین می‌کند که آیا ردیف‌های زوج باید با قالب‌بندی متفاوتی رسم شوند. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | تعیین می‌کند که آیا ردیف‌های زوج باید با قالب‌بندی متفاوتی رسم شوند. |
| [getVerticalBanding()](#getVerticalBanding--) | تعیین می‌کند که آیا ستون‌های زوج باید با قالب‌بندی متفاوتی رسم شوند. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | تعیین می‌کند که آیا ستون‌های زوج باید با قالب‌بندی متفاوتی رسم شوند. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | تنظیم خواص قالب‌بندی بخشی تعریف‌شده برای تمام بخش‌های سلول‌های جدول. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | تنظیم خواص قالب‌بندی پاراگراف تعریف‌شده برای تمام پاراگراف‌های سلول‌های جدول. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | تنظیم خواص قالب‌بندی فریم متن تعریف‌شده برای تمام فریم‌های متن سلول‌های جدول. |
| [getFillFormat()](#getFillFormat--) | شیء TableFormat.FillFormat را که شامل قالب‌بندی پر کردن برای جدول است بر می‌گرداند. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

سلول را در ستون و ردیف مشخص‌شده بر می‌گرداند. فقط-خواندنی [Cell](../../com.aspose.slides/cell).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Returns:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

مجموعه سطرها را بر می‌گرداند. فقط-خواندنی [IRowCollection](../../com.aspose.slides/irowcollection).

**Returns:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

مجموعه ستون‌ها را بر می‌گرداند. فقط-خواندنی [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Returns:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

شیء TableFormat را که شامل خواص قالب‌بندی برای این جدول است بر می‌گرداند. فقط-خواندنی [ITableFormat](../../com.aspose.slides/itableformat).

**Returns:**
[ITableFormat](../../com.aspose.slides/itableformat)
### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

ادغام سلول‌های همجوار.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | سلول برای ادغام. |
| cell2 | [ICell](../../com.aspose.slides/icell) | سلول برای ادغام. |
| allowSplitting | boolean | صحیح برای اجازهٔ تقسیم سلول‌ها. |

**Returns:**
[ICell](../../com.aspose.slides/icell) - سلول ادغام‌شده.
### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

دریافت یا تنظیم سبک جدول داخلی. خواندنی-نوشتنی [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Returns:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

دریافت یا تنظیم سبک جدول داخلی. خواندنی-نوشتنی [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

تعیین می‌کند که آیا جدول ترتیب خوانش راست به چپ دارد یا خیر. خواندنی-نوشتنی boolean .

**Returns:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

تعیین می‌کند که آیا جدول ترتیب خوانش راست به چپ دارد یا خیر. خواندنی-نوشتنی boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

تعیین می‌کند که آیا ردیف اول جدول باید با قالب‌بندی ویژه‌ای رسم شود. خواندنی-نوشتنی boolean .

**Returns:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

تعیین می‌کند که آیا ردیف اول جدول باید با قالب‌بندی ویژه‌ای رسم شود. خواندنی-نوشتنی boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

تعیین می‌کند که آیا ستون اول جدول باید با قالب‌بندی ویژه‌ای رسم شود. خواندنی-نوشتنی boolean .

**Returns:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

تعیین می‌کند که آیا ستون اول جدول باید با قالب‌بندی ویژه‌ای رسم شود. خواندنی-نوشتنی boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

تعیین می‌کند که آیا آخرین ردیف جدول باید با قالب‌بندی ویژه‌ای رسم شود. خواندنی-نوشتنی boolean .

**Returns:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

تعیین می‌کند که آیا آخرین ردیف جدول باید با قالب‌بندی ویژه‌ای رسم شود. خواندنی-نوشتنی boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

تعیین می‌کند که آیا آخرین ستون جدول باید با قالب‌بندی ویژه‌ای رسم شود. خواندنی-نوشتنی boolean .

**Returns:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

تعیین می‌کند که آیا آخرین ستون جدول باید با قالب‌بندی ویژه‌ای رسم شود. خواندنی-نوشتنی boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

تعیین می‌کند که آیا ردیف‌های زوج باید با قالب‌بندی متفاوتی رسم شوند. خواندنی-نوشتنی boolean .

**Returns:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

تعیین می‌کند که آیا ردیف‌های زوج باید با قالب‌بندی متفاوتی رسم شوند. خواندنی-نوشتنی boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

تعیین می‌کند که آیا ستون‌های زوج باید با قالب‌بندی متفاوتی رسم شوند. خواندنی-نوشتنی boolean .

**Returns:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

تعیین می‌کند که آیا ستون‌های زوج باید با قالب‌بندی متفاوتی رسم شوند. خواندنی-نوشتنی boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

تنظیم خواص قالب‌بندی بخشی تعریف‌شده برای تمام بخش‌های سلول‌های جدول.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | شیء IPortionFormat با خصوصیات لازم تنظیم‌شده. |
### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

تنظیم خواص قالب‌بندی پاراگراف تعریف‌شده برای تمام پاراگراف‌های سلول‌های جدول.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | شیء IParagraphFormat با خصوصیات لازم تنظیم‌شده. |
### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

تنظیم خواص قالب‌بندی فریم متن تعریف‌شده برای تمام فریم‌های متن سلول‌های جدول.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | شیء ITextFrameFormat با خصوصیات لازم تنظیم‌شده. |
### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

شیء TableFormat.FillFormat را که شامل قالب‌بندی پر کردن برای جدول است بر می‌گرداند. فقط-خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)