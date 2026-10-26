---
title: MathMatrix
second_title: مرجع API Aspose.Slides برای جاوا
description: شیء Matrix را که از عناصر فرزند تشکیل شده و در یک یا چند ردیف و ستون چیده شده‌اند، مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/mathmatrix/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

مشخص می‌کند که شیء Matrix شامل عناصر فرزند است که در یک یا چند ردیف و ستون چینیده‌اند. مهم است که توجه داشته باشید ماتریس‌ها delimiter داخلی ندارند. برای قرار دادن ماتریس در براکت‌ها باید از شیء delimiter (IMathDelimiter) استفاده کنید. می‌توان از آرگومان‌های null برای ایجاد فاصله در ماتریس‌ها استفاده کرد.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | یک نمونه جدید از کلاس MathMatrix را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getRowCount()](#getRowCount--) | تعداد ردیف‌ها در ماتریس |
| [getColumnCount()](#getColumnCount--) | تعداد ستون‌ها در ماتریس |
| [getHidePlaceholders()](#getHidePlaceholders--) | پنهان کردن نگهدارنده‌ها برای عناصر خالی ماتریس Default: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | پنهان کردن نگهدارنده‌ها برای عناصر خالی ماتریس Default: false |
| [getBaseJustification()](#getBaseJustification--) | جهت‌گیری عمودی نسبت به متن اطراف را مشخص می‌کند. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | جهت‌گیری عمودی نسبت به متن اطراف را مشخص می‌کند. |
| [getMinColumnWidth()](#getMinColumnWidth--) | حداقل عرض ستون بر حسب twips (1/20 ام نقطه) فاصله شکاف (که به عنوان «Column Gap» یا «Gap Width» نیز شناخته می‌شود) به MinColumnWidth افزوده می‌شود تا کل فاصله ستون‌های ماتریس (فاصله بین لبه‌های مشابه ستون‌های مختلف) تعیین شود. |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | حداقل عرض ستون بر حسب twips (1/20 ام نقطه) فاصله شکاف (که به عنوان «Column Gap» یا «Gap Width» نیز شناخته می‌شود) به MinColumnWidth افزوده می‌شود تا کل فاصله ستون‌های ماتریس (فاصله بین لبه‌های مشابه ستون‌های مختلف) تعیین شود. |
| [getColumnGapRule()](#getColumnGapRule--) | نوع فاصله افقی بین ستون‌های ماتریس؛ واحدهای فاصله افقی می‌توانند em یا point باشند (به صورت twips ذخیره می‌شوند). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | نوع فاصله افقی بین ستون‌های ماتریس؛ واحدهای فاصله افقی می‌توانند em یا point باشند (به صورت twips ذخیره می‌شوند). |
| [getColumnGap()](#getColumnGap--) | مقدار فاصله افقی بین ستون‌های ماتریس؛ اگر ColumnGapRule برابر 3 («Exactly») باشد، واحد به صورت twips (1/20 ام نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 («Multiple») باشد، واحد به صورت تعداد گام‌های 0.5 em تفسیر می‌شود. |
| [setColumnGap(long value)](#setColumnGap-long-) | مقدار فاصله افقی بین ستون‌های ماتریس؛ اگر ColumnGapRule برابر 3 («Exactly») باشد، واحد به صورت twips (1/20 ام نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 («Multiple») باشد، واحد به صورت تعداد گام‌های 0.5 em تفسیر می‌شود. |
| [getRowGapRule()](#getRowGapRule--) | نوع فاصله عمودی بین ردیف‌های ماتریس؛ واحدهای فاصله عمودی می‌توانند line یا point باشند (به صورت twips ذخیره می‌شوند). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | نوع فاصله عمودی بین ردیف‌های ماتریس؛ واحدهای فاصله عمودی می‌توانند line یا point باشند (به صورت twips ذخیره می‌شوند). |
| [getRowGap()](#getRowGap--) | مقدار فاصله عمودی بین ردیف‌های ماتریس؛ اگر RowGapRule برابر 3 («Exactly») باشد، واحد به صورت twips (1/20 ام نقطه) تفسیر می‌شود. اگر RowGapRule برابر 4 («Multiple») باشد، واحد به صورت نصف خط‌ها تفسیر می‌شود. |
| [setRowGap(long value)](#setRowGap-long-) | مقدار فاصله عمودی بین ردیف‌های ماتریس؛ اگر RowGapRule برابر 3 («Exactly») باشد، واحد به صورت twips (1/20 ام نقطه) تفسیر می‌شود. اگر RowGapRule برابر 4 («Multiple») باشد، واحد به صورت نصف خط‌ها تفسیر می‌شود. |
| [get_Item(int row, int column)](#get-Item-int-int-) | عنصر ماتریس |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | عنصر ماتریس |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | ویژگی‌های کاراکترهای کنترل |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | دریافت تنظیم افقی ستون مشخص شده |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | تنظیم تنظیم افقی ستون مشخص شده |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | تنظیم تنظیم افقی ستون‌های مشخص شده |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | افزودن یک ردیف جدید قبل از ردیف مشخص شده؛ در ابتدا تمام عناصر ردیف جدید null هستند. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | افزودن یک ردیف جدید بعد از ردیف مشخص شده؛ در ابتدا تمام عناصر ردیف جدید null هستند. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | حذف ردیف مشخص شده |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | افزودن یک ستون جدید قبل از ستون مشخص شده؛ در ابتدا تمام عناصر ستون جدید null هستند. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | افزودن یک ستون جدید بعد از ستون مشخص شده؛ در ابتدا تمام عناصر ستون جدید null هستند. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | حذف ستون مشخص شده |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

یک نمونه جدید از کلاس MathMatrix را مقداردهی اولیه می‌کند.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rowCount | int | تعداد ردیف |
| columnCount | int | تعداد ستون |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
```

تعداد ردیف‌ها در ماتریس

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**بازگرداندن:**
int
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

تعداد ستون‌ها در ماتریس

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**بازگرداندن:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public final boolean getHidePlaceholders()
```

پنهان کردن نگهدارنده‌ها برای عناصر خالی ماتریس Default: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**بازگرداندن:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public final void setHidePlaceholders(boolean value)
```

پنهان کردن نگهدارنده‌ها برای عناصر خالی ماتریس Default: false

--------------------

> ```
> مثال:
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
public final int getBaseJustification()
```

جهت‌گیری عمودی نسبت به متن اطراف را مشخص می‌کند. مقادیر ممکن top، bottom و center هستند. پیش‌فرض: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**بازگرداندن:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

جهت‌گیری عمودی نسبت به متن اطراف را مشخص می‌کند. مقادیر ممکن top، bottom و center هستند. پیش‌فرض: Center

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
public final long getMinColumnWidth()
```

حداقل عرض ستون بر حسب twips (1/20 ام نقطه) فاصله شکاف (که به عنوان «Column Gap» یا «Gap Width» نیز شناخته می‌شود) به MinColumnWidth افزوده می‌شود تا کل فاصله ستون‌های ماتریس (فاصله بین لبه‌های مشابه ستون‌های مختلف) تعیین شود. پیش‌فرض: 0.

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**بازگرداندن:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```

حداقل عرض ستون بر حسب twips (1/20 ام نقطه) فاصله شکاف (که به عنوان «Column Gap» یا «Gap Width» نیز شناخته می‌شود) به MinColumnWidth افزوده می‌شود تا کل فاصله ستون‌های ماتریس (فاصله بین لبه‌های مشابه ستون‌های مختلف) تعیین شود. پیش‌فرض: 0.

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
public final int getColumnGapRule()
```

نوع فاصله افقی بین ستون‌های ماتریس؛ واحدهای فاصله افقی می‌توانند em یا point باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**بازگرداندن:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```

نوع فاصله افقی بین ستون‌های ماتریس؛ واحدهای فاصله افقی می‌توانند em یا point باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)

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
public final long getColumnGap()
```

مقدار فاصله افقی بین ستون‌های ماتریس؛ اگر ColumnGapRule برابر 3 («Exactly») باشد، واحد به صورت twips (1/20 ام نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 («Multiple») باشد، واحد به صورت تعداد گام‌های 0.5 em تفسیر می‌شود. در سایر موارد نادیده گرفته می‌شود. پیش‌فرض: 0

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**بازگرداندن:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```

مقدار فاصله افقی بین ستون‌های ماتریس؛ اگر ColumnGapRule برابر 3 («Exactly») باشد، واحد به صورت twips (1/20 ام نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 («Multiple») باشد، واحد به صورت تعداد گام‌های 0.5 em تفسیر می‌شود. در سایر موارد نادیده گرفته می‌شود. پیش‌فرض: 0

--------------------

> ```
> مثال:
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
public final int getRowGapRule()
```

نوع فاصله عمودی بین ردیف‌های ماتریس؛ واحدهای فاصله عمودی می‌توانند line یا point باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**بازگرداندن:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public final void setRowGapRule(int value)
```

نوع فاصله عمودی بین ردیف‌های ماتریس؛ واحدهای فاصله عمودی می‌توانند line یا point باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)

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
public final long getRowGap()
```

مقدار فاصله عمودی بین ردیف‌های ماتریس؛ اگر RowGapRule برابر 3 («Exactly») باشد، واحد به صورت twips (1/20 ام نقطه) تفسیر می‌شود. اگر RowGapRule برابر 4 («Multiple») باشد، واحد به صورت نصف خط‌ها تفسیر می‌شود. پیش‌فرض: 0

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**بازگرداندن:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```

مقدار فاصله عمودی بین ردیف‌های ماتریس؛ اگر RowGapRule برابر 3 («Exactly») باشد، واحد به صورت twips (1/20 ام نقطه) تفسیر می‌شود. اگر RowGapRule برابر 4 («Multiple») باشد، واحد به صورت نصف خط‌ها تفسیر می‌شود. پیش‌فرض: 0

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

عنصر ماتریس

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
| row | int | اندیس صفر-مبنا برای ردیف موردنظر |
| column | int | اندیس صفر-مبنا برای ستون موردنظر |

**بازگرداندن:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

عنصر ماتریس

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| row | int | اندیس صفر-مبنا برای ردیف موردنظر |
| column | int | اندیس صفر-مبنا برای ستون موردنظر |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

ویژگی‌های کاراکترهای کنترل

**بازگرداندن:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

دریافت تنظیم افقی ستون مشخص شده

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | int | اندیس صفر-مبنا برای ستون |

**بازگرداندن:**
int - تنظیم افقی ستون مشخص شده
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

تنظیم تنظیم افقی ستون مشخص شده

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
| columnIndex | int | اندیس صفر-مبنا برای ستون |
| val | int | مقدار جدید تنظیم افقی ستون‌های مشخص شده |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

تنظیم تنظیم افقی ستون‌های مشخص شده

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | int | اندیس صفر-مبنا برای اولین ستون موردنظر |
| columnsCount | long | تعداد ستون‌های موردنظر برای تنظیم |
| val | int | مقدار جدید تنظیم افقی ستون‌های مشخص شده |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

افزودن یک ردیف جدید قبل از ردیف مشخص شده؛ در ابتدا تمام عناصر ردیف جدید null هستند.

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rowIndex | int | اندیس ردیفی که قبل از آن ردیف جدیدی درج می‌شود |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

افزودن یک ردیف جدید بعد از ردیف مشخص شده؛ در ابتدا تمام عناصر ردیف جدید null هستند.

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
| rowIndex | int | اندیس ردیفی که بعد از آن ردیف جدیدی درج می‌شود |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

حذف ردیف مشخص شده

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rowIndex | int | اندیس صفر-مبنا برای ردیف موردنظر برای حذف. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

افزودن یک ستون جدید قبل از ستون مشخص شده؛ در ابتدا تمام عناصر ستون جدید null هستند.

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | int | اندیس ستون قبل از آن ستونی جدید درج می‌شود |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

افزودن یک ستون جدید بعد از ستون مشخص شده؛ در ابتدا تمام عناصر ستون جدید null هستند.

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | int | اندیس ستونی که بعد از آن ستونی جدید درج می‌شود |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```

حذف ستون مشخص شده

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | int | اندیس صفر-مبنا برای ستون موردنظر برای حذف. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

دریافت عناصر فرزند

**بازگرداندن:**
com.aspose.slides.IMathElement[]