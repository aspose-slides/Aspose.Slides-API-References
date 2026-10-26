---
title: Table
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک جدول را روی اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/table/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.ITable](../../com.aspose.slides/itable)  
```
public final class Table extends GraphicalObject implements ITable
```

نمایش یک جدول روی اسلاید.

## متدها

| متد | شرح |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | سلول را در ایندکس‌های ستون و ردیف مشخص‌شده برمی‌گرداند. |
| [getRows()](#getRows--) | مجموعه ردیف‌ها را برمی‌گرداند. |
| [getColumns()](#getColumns--) | مجموعه ستون‌ها را برمی‌گرداند. |
| [getTableFormat()](#getTableFormat--) | شیء TableFormat که شامل ویژگی‌های قالب‌بندی برای این جدول است را برمی‌گرداند. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | سلول‌های همسایه را ترکیب می‌کند. |
| [getStylePreset()](#getStylePreset--) | سبک جدول پیش‌ساخته را دریافت یا تنظیم می‌کند. |
| [setStylePreset(int value)](#setStylePreset-int-) | سبک جدول پیش‌ساخته را دریافت یا تنظیم می‌کند. |
| [getRightToLeft()](#getRightToLeft--) | تشخیص می‌دهد که آیا جدول ترتیب خواندن راست به چپ دارد یا خیر. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | تشخیص می‌دهد که آیا جدول ترتیب خواندن راست به چپ دارد یا خیر. |
| [getFirstRow()](#getFirstRow--) | تشخیص می‌دهد که آیا ردیف اول جدول باید با قالب‌بندی ویژه رسم شود یا خیر. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | تشخیص می‌دهد که آیا ردیف اول جدول باید با قالب‌بندی ویژه رسم شود یا خیر. |
| [getFirstCol()](#getFirstCol--) | تشخیص می‌دهد که آیا ستون اول جدول باید با قالب‌بندی ویژه رسم شود یا خیر. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | تشخیص می‌دهد که آیا ستون اول جدول باید با قالب‌بندی ویژه رسم شود یا خیر. |
| [getLastRow()](#getLastRow--) | تشخیص می‌دهد که آیا ردیف آخر جدول باید با قالب‌بندی ویژه رسم شود یا خیر. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | تشخیص می‌دهد که آیا ردیف آخر جدول باید با قالب‌بندی ویژه رسم شود یا خیر. |
| [getLastCol()](#getLastCol--) | تشخیص می‌دهد که آیا ستون آخر جدول باید با قالب‌بندی ویژه رسم شود یا خیر. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | تشخیص می‌دهد که آیا ستون آخر جدول باید با قالب‌بندی ویژه رسم شود یا خیر. |
| [getHorizontalBanding()](#getHorizontalBanding--) | تشخیص می‌دهد که آیا ردیف‌های زوج باید با قالب‌بندی متفاوت رسم شوند. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | تشخیص می‌دهد که آیا ردیف‌های زوج باید با قالب‌بندی متفاوت رسم شوند. |
| [getVerticalBanding()](#getVerticalBanding--) | تشخیص می‌دهد که آیا ستون‌های زوج باید با قالب‌بندی متفاوت رسم شوند. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | تشخیص می‌دهد که آیا ستون‌های زوج باید با قالب‌بندی متفاوت رسم شوند. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | ویژگی‌های قالب‌بندی بخش‌های تعریف‌شده را برای تمام بخش‌های سلول‌های جدول تنظیم می‌کند. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده را برای تمام پاراگراف‌های سلول‌های جدول تنظیم می‌کند. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | ویژگی‌های قالب‌بندی چارچوب متن تعریف‌شده را برای تمام چارچوب‌های متنی سلول‌های جدول تنظیم می‌کند. |
| [getFillFormat()](#getFillFormat--) | شیء TableFormat.FillFormat که شامل قالب‌بندی پر کردن برای جدول است را برمی‌گرداند. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

سلول را در ایندکس‌های ستون و ردیف مشخص‌شده برمی‌گرداند. فقط قابل خواندن [Cell](../../com.aspose.slides/cell).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**بازگشت:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

مجموعه ردیف‌ها را برمی‌گرداند. فقط قابل خواندن [IRowCollection](../../com.aspose.slides/irowcollection).

**بازگشت:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

مجموعه ستون‌ها را برمی‌گرداند. فقط قابل خواندن [IColumnCollection](../../com.aspose.slides/icolumncollection).

**بازگشت:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

شیء TableFormat که شامل ویژگی‌های قالب‌بندی برای این جدول است را برمی‌گرداند. فقط قابل خواندن [ITableFormat](../../com.aspose.slides/itableformat).

**بازگشت:**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

سلول‌های همسایه را ترکیب می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | سلول برای ترکیب. |
| cell2 | [ICell](../../com.aspose.slides/icell) | سلول برای ترکیب. |
| allowSplitting | boolean | true برای اجازه تقسیم سلول‌ها. |

**بازگشت:**
[ICell](../../com.aspose.slides/icell) - سلول ترکیب‌شده.

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

سبک جدول پیش‌ساخته را دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**بازگشت:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

سبک جدول پیش‌ساخته را دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

تشخیص می‌دهد که آیا جدول ترتیب خواندن راست به چپ دارد یا خیر. قابل خواندن/قابل نوشتن boolean.

**بازگشت:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

تشخیص می‌دهد که آیا جدول ترتیب خواندن راست به چپ دارد یا خیر. قابل خواندن/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

تشخیص می‌دهد که آیا ردیف اول جدول باید با قالب‌بندی ویژه رسم شود یا خیر. قابل خواندن/قابل نوشتن boolean.

**بازگشت:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

تشخیص می‌دهد که آیا ردیف اول جدول باید با قالب‌بندی ویژه رسم شود یا خیر. قابل خواندن/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

تشخیص می‌دهد که آیا ستون اول جدول باید با قالب‌بندی ویژه رسم شود یا خیر. قابل خواندن/قابل نوشتن boolean.

**بازگشت:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

تشخیص می‌دهد که آیا ستون اول جدول باید با قالب‌بندی ویژه رسم شود یا خیر. قابل خواندن/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

تشخیص می‌دهد که آیا ردیف آخر جدول باید با قالب‌بندی ویژه رسم شود یا خیر. قابل خواندن/قابل نوشتن boolean.

**بازگشت:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

تشخیص می‌دهد که آیا ردیف آخر جدول باید با قالب‌بندی ویژه رسم شود یا خیر. قابل خواندن/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

تشخیص می‌دهد که آیا ستون آخر جدول باید با قالب‌بندی ویژه رسم شود یا خیر. قابل خواندن/قابل نوشتن boolean.

**بازگشت:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

تشخیص می‌دهد که آیا ستون آخر جدول باید با قالب‌بندی ویژه رسم شود یا خیر. قابل خواندن/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

تشخیص می‌دهد که آیا ردیف‌های زوج باید با قالب‌بندی متفاوت رسم شوند. قابل خواندن/قابل نوشتن boolean.

**بازگشت:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

تشخیص می‌دهد که آیا ردیف‌های زوج باید با قالب‌بندی متفاوت رسم شوند. قابل خواندن/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

تشخیص می‌دهد که آیا ستون‌های زوج باید با قالب‌بندی متفاوت رسم شوند. قابل خواندن/قابل نوشتن boolean.

**بازگشت:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

تشخیص می‌دهد که آیا ستون‌های زوج باید با قالب‌بندی متفاوت رسم شوند. قابل خواندن/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

ویژگی‌های قالب‌بندی بخش‌های تعریف‌شده را برای تمام بخش‌های سلول‌های جدول تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | شیء IPortionFormat با ویژگی‌های لازم تنظیم‌شده. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده را برای تمام پاراگراف‌های سلول‌های جدول تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | شیء IParagraphFormat با ویژگی‌های لازم تنظیم‌شده. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

ویژگی‌های قالب‌بندی چارچوب متن تعریف‌شده را برای تمام چارچوب‌های متنی سلول‌های جدول تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | شیء ITextFrameFormat با ویژگی‌های لازم تنظیم‌شده. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

شیء TableFormat.FillFormat که شامل قالب‌بندی پر کردن برای جدول است را برمی‌گرداند. فقط قابل خواندن [IFillFormat](../../com.aspose.slides/ifillformat).

**بازگشت:**
[IFillFormat](../../com.aspose.slides/ifillformat)