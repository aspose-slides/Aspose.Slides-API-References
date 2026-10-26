---
title: IMathMatrix
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: شیء Matrix را که شامل عناصر فرزند در یک یا چند سطر و ستون چیده شده است، مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/imathmatrix/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

مشخص‌کنندهٔ شیء Matrix است که شامل عناصر فرزند در یک یا چند سطر و ستون چیده شده‌اند. مهم است که توجه داشته باشید ماتریس‌ها delimiters داخلی ندارند. برای قرار دادن ماتریس در براکت‌ها باید از شیء delimiter (IMathDelimiter) استفاده کنید. می‌توان از آرگومان‌های null برای ایجاد فواصل در ماتریس‌ها استفاده کرد.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | Elements of matrix |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Elements of matrix |
| [getRowCount()](#getRowCount--) | Number of rows in the matrix |
| [getColumnCount()](#getColumnCount--) | Number of columns in the matrix |
| [getHidePlaceholders()](#getHidePlaceholders--) | Hide the placeholders for empty matrix elements Default: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Hide the placeholders for empty matrix elements Default: false |
| [getBaseJustification()](#getBaseJustification--) | Specifies the vertical justification respect to surrounding text. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specifies the vertical justification respect to surrounding text. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). |
| [getColumnGapRule()](#getColumnGapRule--) | The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). |
| [getColumnGap()](#getColumnGap--) | The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. |
| [setColumnGap(long value)](#setColumnGap-long-) | The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. |
| [getRowGapRule()](#getRowGapRule--) | The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). |
| [getRowGap()](#getRowGap--) | The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. |
| [setRowGap(long value)](#setRowGap-long-) | The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Get the horizontal alignment of the specified column |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Set the horizontal alignment of the specified column |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Set the horizontal alignment of the specified columns |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Insert a new row before the specified one Initially all elements in the new row are null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Insert a new row after the specified one Initially all elements in the new row are null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Deletes the specified row |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Insert a new column before the specified one Initially all elements in the new column are null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Insert a new column after the specified one Initially all elements in the new column are null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Deletes the specified column |
### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

عناصر ماتریس

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| row | int | ایندکس صفر مبنا برای سطر مورد نظر |
| column | int | ایندکس صفر مبنا برای ستون مورد نظر |

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

عناصر ماتریس

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| row | int | ایندکس صفر مبنا برای سطر مورد نظر |
| column | int | ایندکس صفر مبنا برای ستون مورد نظر |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
```

تعداد سطرهای Matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**بازگشت:**
int
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

تعداد ستون‌های Matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**بازگشت:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

مخفی کردن نگهدارنده‌ها برای عناصر خالی Matrix پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**بازگشت:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

مخفی کردن نگهدارنده‌ها برای عناصر خالی Matrix پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

مشخص‌کنندهٔ تراز عمودی نسبت به متن اطراف. مقادیر ممکن top، bottom و center هستند. پیش‌فرض: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**بازگشت:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

مشخص‌کنندهٔ تراز عمودی نسبت به متن اطراف. مقادیر ممکن top، bottom و center هستند. پیش‌فرض: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public abstract long getMinColumnWidth()
```

حداقل عرض ستون بر حسب twips (1/20 نقطه). فاصلهٔ گپ (که به نام «Column Gap» یا «Gap Width» نیز شناخته می‌شود) به MinColumnWidth اضافه می‌شود تا کل فاصلهٔ ستون‌های ماتریس تعیین شود. پیش‌فرض: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**بازگشت:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

حداقل عرض ستون بر حسب twips (1/20 نقطه). فاصلهٔ گپ (که به نام «Column Gap» یا «Gap Width» نیز شناخته می‌شود) به MinColumnWidth اضافه می‌شود تا کل فاصلهٔ ستون‌های ماتریس تعیین شود. پیش‌فرض: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public abstract int getColumnGapRule()
```

نوع فاصلهٔ افقی بین ستون‌های Matrix؛ واحدهای فاصله می‌توانند em یا point باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**بازگشت:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```

نوع فاصلهٔ افقی بین ستون‌های Matrix؛ واحدهای فاصله می‌توانند em یا point باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public abstract long getColumnGap()
```

مقدار فاصلهٔ افقی بین ستون‌های Matrix؛ اگر ColumnGapRule برابر 3 («Exactly») باشد، واحد به صورت twips تعبیر می‌شود؛ اگر ColumnGapRule برابر 4 («Multiple») باشد، واحد به صورت تعداد افزاینده‌های 0.5 em تعبیر می‌شود. در موارد دیگر نادیده گرفته می‌شود. پیش‌فرض: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**بازگشت:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

مقدار فاصلهٔ افقی بین ستون‌های Matrix؛ اگر ColumnGapRule برابر 3 («Exactly») باشد، واحد به صورت twips تعبیر می‌شود؛ اگر ColumnGapRule برابر 4 («Multiple») باشد، واحد به صورت تعداد افزاینده‌های 0.5 em تعبیر می‌شود. در موارد دیگر نادیده گرفته می‌شود. پیش‌فرض: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public abstract int getRowGapRule()
```

نوع فاصلهٔ عمودی بین سطرهای Matrix؛ واحدهای فاصله می‌توانند line یا point باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**بازگشت:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

نوع فاصلهٔ عمودی بین سطرهای Matrix؛ واحدهای فاصله می‌توانند line یا point باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public abstract long getRowGap()
```

مقدار فاصلهٔ عمودی بین سطرهای Matrix؛ اگر RowGapRule برابر 3 («Exactly») باشد، واحد به صورت twips تعبیر می‌شود؛ اگر RowGapRule برابر 4 («Multiple») باشد، واحد به صورت نصف خط‌ها تعبیر می‌شود. پیش‌فرض: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**بازگشت:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```

مقدار فاصلهٔ عمودی بین سطرهای Matrix؛ اگر RowGapRule برابر 3 («Exactly») باشد، واحد به صورت twips تعبیر می‌شود؛ اگر RowGapRule برابر 4 («Multiple») باشد، واحد به صورت نصف خط‌ها تعبیر می‌شود. پیش‌فرض: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

دریافت تراز افقی ستون مشخص‌شده

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | int | ایندکس صفر مبنا برای ستون |

**بازگشت:**
int - Horizontal Alignment of specified column
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

تنظیم تراز افقی ستون مشخص‌شده

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | int | ایندکس صفر مبنا برای ستون |
| val | int | مقدار جدید تراز افقی ستون مشخص‌شده |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

تنظیم تراز افقی ستون‌های مشخص‌شده

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | int | ایندکس صفر مبنا برای اولین ستونی که تراز آن تنظیم می‌شود |
| columnsCount | long | تعداد ستون‌هایی که تراز برای آن‌ها تعیین می‌شود |
| val | int | مقدار جدید تراز افقی ستون مشخص‌شده |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

درج یک سطر جدید قبل از سطر مورد نظر. در ابتدا تمام عناصر سطر جدید null هستند.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rowIndex | int | ایندکس سطری که قبل از آن سطر جدید قرار می‌گیرد |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

درج یک سطر جدید پس از سطر مورد نظر. در ابتدا تمام عناصر سطر جدید null هستند.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rowIndex | int | ایندکس سطری که پس از آن سطر جدید قرار می‌گیرد |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

حذف سطر مشخص‌شده

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rowIndex | int | ایندکس صفر مبنا برای سطر مورد نظر برای حذف. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

درج یک ستون جدید قبل از ستون مورد نظر. در ابتدا تمام عناصر ستون جدید null هستند.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | int | ایندکس ستونی که قبل از آن ستون جدید قرار می‌گیرد |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

درج یک ستون جدید پس از ستون مورد نظر. در ابتدا تمام عناصر ستون جدید null هستند.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | int | ایندکس ستونی که پس از آن ستون جدید قرار می‌گیرد |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

حذف ستون مشخص‌شده

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | int | ایندکس صفر مبنا برای ستون مورد نظر برای حذف. |