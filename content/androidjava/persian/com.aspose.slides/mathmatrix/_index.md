---
title: MathMatrix
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: آبجکت Matrix را مشخص می‌کند که از عناصر فرزند تشکیل شده است که در یک یا چند ردیف و ستون چیده شده‌اند.
type: docs
url: /fa/com.aspose.slides/mathmatrix/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**همه رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

آبجکت Matrix را مشخص می‌کند که شامل عناصر فرزند است که در یک یا چند ردیف و ستون چیده شده‌اند. مهم است که توجه کنید ماتریس‌ها delimiters داخلی ندارند. برای قرار دادن ماتریس در پرانتزها باید از شیء delimiter (IMathDelimiter) استفاده کنید. آرگومان‌های null می‌توانند برای ایجاد فواصل در ماتریس‌ها استفاده شوند.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## سازندگان

| سازنده | توضیح |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | یک نمونه جدید از کلاس MathMatrix را مقداردهی اولیه می‌کند. |

## متدها

| متد | توضیح |
| --- | --- |
| [getRowCount()](#getRowCount--) | تعداد ردیف‌ها در ماتریس |
| [getColumnCount()](#getColumnCount--) | تعداد ستون‌ها در ماتریس |
| [getHidePlaceholders()](#getHidePlaceholders--) | پنهان کردن جای‌دارها برای عناصر خالی ماتریس. پیش‌فرض: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | پنهان کردن جای‌دارها برای عناصر خالی ماتریس. پیش‌فرض: false |
| [getBaseJustification()](#getBaseJustification--) | جهت‌گیری عمودی نسبت به متن اطراف را مشخص می‌کند. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | جهت‌گیری عمودی نسبت به متن اطراف را مشخص می‌کند. |
| [getMinColumnWidth()](#getMinColumnWidth--) | حداقل عرض ستون بر حسب twips (1/20 نقطه) فاصله بین ستون‌ها (که به عنوان \\u201cColumn Gap\\u201d یا \\u201cGap Width\\u201d نیز نامیده می‌شود) به MinColumnWidth اضافه می‌شود تا کل فاصله ستون‌های ماتریس (فاصله بین لبه‌های مشابه ستون‌های مختلف) محاسبه شود. |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | حداقل عرض ستون بر حسب twips (1/20 نقطه) فاصله بین ستون‌ها (که به عنوان \\u201cColumn Gap\\u201d یا \\u201cGap Width\\u201d نیز نامیده می‌شود) به MinColumnWidth اضافه می‌شود تا کل فاصله ستون‌های ماتریس (فاصله بین لبه‌های مشابه ستون‌های مختلف) محاسبه شود. |
| [getColumnGapRule()](#getColumnGapRule--) | نوع فاصله افقی بین ستون‌های یک ماتریس؛ واحدهای فاصله افقی می‌توانند em یا point باشند (به صورت twips ذخیره می‌شوند). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | نوع فاصله افقی بین ستون‌های یک ماتریس؛ واحدهای فاصله افقی می‌توانند em یا point باشند (به صورت twips ذخیره می‌شوند). |
| [getColumnGap()](#getColumnGap--) | مقدار فاصله افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule برابر 3 (\"Exactly\") باشد، واحد به عنوان twips (1/20 نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان تعداد افزایش 0.5 em تفسیر می‌شود. |
| [setColumnGap(long value)](#setColumnGap-long-) | مقدار فاصله افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule برابر 3 (\"Exactly\") باشد، واحد به عنوان twips (1/20 نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان تعداد افزایش 0.5 em تفسیر می‌شود. |
| [getRowGapRule()](#getRowGapRule--) | نوع فاصله عمودی بین ردیف‌های یک ماتریس؛ واحدهای فاصله عمودی می‌توانند خطوط یا نقاط (به صورت twips) باشند. |
| [setRowGapRule(int value)](#setRowGapRule-int-) | نوع فاصله عمودی بین ردیف‌های یک ماتریس؛ واحدهای فاصله عمودی می‌توانند خطوط یا نقاط (به صورت twips) باشند. |
| [getRowGap()](#getRowGap--) | مقدار فاصله عمودی بین ردیف‌های یک ماتریس؛ اگر RowGapRule برابر 3 (\"Exactly\") باشد، واحد به عنوان twips (1/20 نقطه) تفسیر می‌شود. اگر RowGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان نیم‌خط‌ها تفسیر می‌شود. |
| [setRowGap(long value)](#setRowGap-long-) | مقدار فاصله عمودی بین ردیف‌های یک ماتریس؛ اگر RowGapRule برابر 3 (\"Exactly\") باشد، واحد به عنوان twips (1/20 نقطه) تفسیر می‌شود. اگر RowGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان نیم‌خط‌ها تفسیر می‌شود. |
| [get_Item(int row, int column)](#get-Item-int-int-) | عنصر ماتریس |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | عنصر ماتریس |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | ویژگی‌های کاراکتر کنترل |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | دریافت تراز افقی ستون مشخص شده |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | تنظیم تراز افقی ستون مشخص شده |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | تنظیم تراز افقی ستون‌های مشخص شده |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | درج یک ردیف جدید قبل از ردیف مشخص شده. در ابتدا تمام عناصر ردیف جدید null هستند. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | درج یک ردیف جدید پس از ردیف مشخص شده. در ابتدا تمام عناصر ردیف جدید null هستند. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | حذف ردیف مشخص شده |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | درج یک ستون جدید قبل از ستون مشخص شده. در ابتدا تمام عناصر ستون جدید null هستند. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | درج یک ستون جدید پس از ستون مشخص شده. در ابتدا تمام عناصر ستون جدید null هستند. |
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

**بازگشت:**
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

**بازگشت:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public final boolean getHidePlaceholders()
```

پنهان کردن جای‌دارها برای عناصر خالی ماتریس. پیش‌فرض: false

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
public final void setHidePlaceholders(boolean value)
```

پنهان کردن جای‌دارها برای عناصر خالی ماتریس. پیش‌فرض: false

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

**بازگشت:**
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

حداقل عرض ستون بر حسب twips (1/20 نقطه) فاصله بین ستون‌ها (که به عنوان \\u201cColumn Gap\\u201d یا \\u201cGap Width\\u201d نیز نامیده می‌شود) به MinColumnWidth اضافه می‌شود تا کل فاصله ستون‌های ماتریس (فاصله بین لبه‌های مشابه ستون‌های مختلف) محاسبه شود. پیش‌فرض: 0.

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
public final void setMinColumnWidth(long value)
```

حداقل عرض ستون بر حسب twips (1/20 نقطه) فاصله بین ستون‌ها (که به عنوان \\u201cColumn Gap\\u201d یا \\u201cGap Width\\u201d نیز نامیده می‌شود) به MinColumnWidth اضافه می‌شود تا کل فاصله ستون‌های ماتریس (فاصله بین لبه‌های مشابه ستون‌های مختلف) محاسبه شود. پیش‌فرض: 0.

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

نوع فاصله افقی بین ستون‌های یک ماتریس؛ واحدهای فاصله افقی می‌توانند em یا point باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)

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
public final void setColumnGapRule(int value)
```

نوع فاصله افقی بین ستون‌های یک ماتریس؛ واحدهای فاصله افقی می‌توانند em یا point باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)

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

مقدار فاصله افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule برابر 3 (\"Exactly\") باشد، واحد به عنوان twips (1/20 نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان تعداد افزایش 0.5 em تفسیر می‌شود. در موارد دیگر نادیده گرفته می‌شود. پیش‌فرض: 0

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
public final void setColumnGap(long value)
```

مقدار فاصله افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule برابر 3 (\"Exactly\") باشد، واحد به عنوان twips (1/20 نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان تعداد افزایش 0.5 em تفسیر می‌شود. در موارد دیگر نادیده گرفته می‌شود. پیش‌فرض: 0

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
public final int getRowGapRule()
```

نوع فاصله عمودی بین ردیف‌های یک ماتریس؛ واحدهای فاصله عمودی می‌توانند خطوط یا نقاط (به صورت twips) باشند. پیش‌فرض: SingleSpacingGap (0)

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
public final void setRowGapRule(int value)
```

نوع فاصله عمودی بین ردیف‌های یک ماتریس؛ واحدهای فاصله عمودی می‌توانند خطوط یا نقاط (به صورت twips) باشند. پیش‌فرض: SingleSpacingGap (0)

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

مقدار فاصله عمودی بین ردیف‌های یک ماتریس؛ اگر RowGapRule برابر 3 (\"Exactly\") باشد، واحد به عنوان twips (1/20 نقطه) تفسیر می‌شود. اگر RowGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان نیم‌خط‌ها تفسیر می‌شود. پیش‌فرض: 0

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
public final void setRowGap(long value)
```

مقدار فاصله عمودی بین ردیف‌های یک ماتریس؛ اگر RowGapRule برابر 3 (\"Exactly\") باشد، واحد به عنوان twips (1/20 نقطه) تفسیر می‌شود. اگر RowGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان نیم‌خط‌ها تفسیر می‌شود. پیش‌فرض: 0

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
| row | int | اندیس صفر-مبانی ردیف برای دریافت مورد |
| column | int | اندیس صفر-مبانی ستون برای دریافت مورد |

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
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
| row | int | اندیس صفر-مبانی ردیف برای دریافت مورد |
| column | int | اندیس صفر-مبانی ستون برای دریافت مورد |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

ویژگی‌های کاراکتر کنترل

**بازگشت:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

دریافت تراز افقی ستون مشخص شده

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
| columnIndex | int | اندیس صفر-مبانی ستون |

**بازگشت:**
int - تراز افقی ستون مشخص شده
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

تنظیم تراز افقی ستون مشخص شده

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
| columnIndex | int | اندیس صفر-مبانی ستون |
| val | int | مقدار جدید تراز افقی ستون مشخص شده |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

تنظیم تراز افقی ستون‌های مشخص شده

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
| columnIndex | int | اندیس صفر-مبانی اولین ستونی که تراز آن تنظیم شود |
| columnsCount | long | تعداد ستون‌هایی که تراز می‌شوند |
| val | int | مقدار جدید تراز افقی ستون‌های مشخص شده |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

درج یک ردیف جدید قبل از ردیف مشخص شده. در ابتدا تمام عناصر ردیف جدید null هستند.

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
| rowIndex | int | اندیس ردیفی که پیش از آن ردیف جدید درج می‌شود |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

درج یک ردیف جدید پس از ردیف مشخص شده. در ابتدا تمام عناصر ردیف جدید null هستند.

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
| rowIndex | int | اندیس ردیفی که پس از آن ردیف جدید درج می‌شود |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

حذف ردیف مشخص شده

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
| rowIndex | int | اندیس صفر-مبانی ردیف برای حذف. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

درج یک ستون جدید قبل از ستون مشخص شده. در ابتدا تمام عناصر ستون جدید null هستند.

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
| columnIndex | int | اندیس ستونی که پیش از آن ستون جدید درج می‌شود |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

درج یک ستون جدید پس از ستون مشخص شده. در ابتدا تمام عناصر ستون جدید null هستند.

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
| columnIndex | int | اندیس ستونی که پس از آن ستون جدید درج می‌شود |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```

حذف ستون مشخص شده

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
| columnIndex | int | اندیس صفر-مبانی ستون برای حذف. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

دریافت عناصر فرزند

**بازگشت:**
com.aspose.slides.IMathElement[]