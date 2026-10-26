---
title: IMathMatrix
second_title: Aspose.Slides برای Java مرجع API
description: شی Matrix را مشخص می‌کند که از عناصر فرزند تشکیل شده و در یک یا چند ردیف و ستون چیده شده‌اند.
type: docs
url: /fa/com.aspose.slides/imathmatrix/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

شی Matrix را مشخص می‌کند که از عناصر فرزند تشکیل شده‌اند و در یک یا چند ردیف و ستون چیده شده‌اند. مهم است که توجه داشته باشید ماتریس‌ها محدود‌کننده‌های داخلی ندارند. برای قرار دادن ماتریس در کروشه‌ها باید از شی محدود‌کننده (IMathDelimiter) استفاده کنید. می‌توان از آرگومان‌های Null برای ایجاد فواصل در ماتریس‌ها استفاده کرد.

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
| [get_Item(int row, int column)](#get-Item-int-int-) | عناصر ماتریس |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | عناصر ماتریس |
| [getRowCount()](#getRowCount--) | تعداد ردیف‌ها در ماتریس |
| [getColumnCount()](#getColumnCount--) | تعداد ستون‌ها در ماتریس |
| [getHidePlaceholders()](#getHidePlaceholders--) | پنهان کردن مکان‌گیرها برای عناصر خالی ماتریس. پیش‌فرض: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | پنهان کردن مکان‌گیرها برای عناصر خالی ماتریس. پیش‌فرض: false |
| [getBaseJustification()](#getBaseJustification--) | جهت‌گیری عمودی نسبت به متن اطراف را مشخص می‌کند. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | جهت‌گیری عمودی نسبت به متن اطراف را مشخص می‌کند. |
| [getMinColumnWidth()](#getMinColumnWidth--) | حداقل عرض ستون به twips (1/20 ام نقطه). فاصله بین ستون‌ها (که به آن \\u201cColumn Gap\\u201d یا \\u201cGap Width\\u201d نیز می‌گویند) به MinColumnWidth اضافه می‌شود تا کل فاصله ستون‌های ماتریس (فاصله بین لبه‌های یکسان ستون‌های مختلف) تعیین شود. |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | حداقل عرض ستون به twips (1/20 ام نقطه). فاصله بین ستون‌ها (که به آن \\u201cColumn Gap\\u201d یا \\u201cGap Width\\u201d نیز می‌گویند) به MinColumnWidth اضافه می‌شود تا کل فاصله ستون‌های ماتریس (فاصله بین لبه‌های یکسان ستون‌های مختلف) تعیین شود. |
| [getColumnGapRule()](#getColumnGapRule--) | نوع فاصله افقی بین ستون‌های یک ماتریس؛ واحدهای فاصله افقی می‌توانند ems یا points باشند (به صورت twips ذخیره می‌شوند). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | نوع فاصله افقی بین ستون‌های یک ماتریس؛ واحدهای فاصله افقی می‌توانند ems یا points باشند (به صورت twips ذخیره می‌شوند). |
| [getColumnGap()](#getColumnGap--) | مقدار فاصله افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule برابر 3 (\"Exactly\") باشد، واحد به عنوان twips (1/20 ام نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان تعداد گام‌های 0.5 em تفسیر می‌شود. |
| [setColumnGap(long value)](#setColumnGap-long-) | مقدار فاصله افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule برابر 3 (\"Exactly\") باشد، واحد به عنوان twips (1/20 ام نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان تعداد گام‌های 0.5 em تفسیر می‌شود. |
| [getRowGapRule()](#getRowGapRule--) | نوع فاصله عمودی بین ردیف‌های یک ماتریس؛ واحدهای فاصله عمودی می‌توانند خطوط یا نقاط باشند (به صورت twips ذخیره می‌شوند). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | نوع فاصله عمودی بین ردیف‌های یک ماتریس؛ واحدهای فاصله عمودی می‌توانند خطوط یا نقاط باشند (به صورت twips ذخیره می‌شوند). |
| [getRowGap()](#getRowGap--) | مقدار فاصله عمودی بین ردیف‌های یک ماتریس؛ اگر RowGapRule برابر 3 (\"Exactly\") باشد، واحد به عنوان twips (1/20 ام نقطه) تفسیر می‌شود. اگر RowGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان نصف خطوط تفسیر می‌شود. |
| [setRowGap(long value)](#setRowGap-long-) | مقدار فاصله عمودی بین ردیف‌های یک ماتریس؛ اگر RowGapRule برابر 3 (\"Exactly\") باشد، واحد به عنوان twips (1/20 ام نقطه) تفسیر می‌شود. اگر RowGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان نصف خطوط تفسیر می‌شود. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | دریافت تراز افقی ستون مشخص‌شده |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | تنظیم تراز افقی ستون مشخص‌شده |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | تنظیم تراز افقی ستون‌های مشخص‌شده |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | درج یک ردیف جدید قبل از ردیف مشخص‌شده. ابتدا تمام عناصر ردیف جدید null هستند. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | درج یک ردیف جدید پس از ردیف مشخص‌شده. ابتدا تمام عناصر ردیف جدید null هستند. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | حذف ردیف مشخص‌شده |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | درج یک ستون جدید قبل از ستون مشخص‌شده. ابتدا تمام عناصر ستون جدید null هستند. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | درج یک ستون جدید پس از ستون مشخص‌شده. ابتدا تمام عناصر ستون جدید null هستند. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | حذف ستون مشخص‌شده |

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
| row | int | اندیس صفر-مبنا برای ردیفی که می‌خواهید آیتم را دریافت کنید |
| column | int | اندیس صفر-مبنا برای ستونی که می‌خواهید آیتم را دریافت کنید |

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
| row | int | اندیس صفر-مبنا برای ردیفی که می‌خواهید آیتم را دریافت کنید |
| column | int | اندیس صفر-مبنا برای ستونی که می‌خواهید آیتم را دریافت کنید |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
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
public abstract int getColumnCount()
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
public abstract boolean getHidePlaceholders()
```

پنهان کردن مکان‌گیرها برای عناصر خالی ماتریس. پیش‌فرض: false

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

پنهان کردن مکان‌گیرها برای عناصر خالی ماتریس. پیش‌فرض: false

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
public abstract void setBaseJustification(int value)
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
public abstract long getMinColumnWidth()
```

حداقل عرض ستون به twips (1/20 ام نقطه). فاصله بین ستون‌ها (که به آن \\u201cColumn Gap\\u201d یا \\u201cGap Width\\u201d نیز می‌گویند) به MinColumnWidth اضافه می‌شود تا کل فاصله ستون‌های ماتریس (فاصله بین لبه‌های یکسان ستون‌های مختلف) تعیین شود. پیش‌فرض: 0.

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

حداقل عرض ستون به twips (1/20 ام نقطه). فاصله بین ستون‌ها (که به آن \\u201cColumn Gap\\u201d یا \\u201cGap Width\\u201d نیز می‌گویند) به MinColumnWidth اضافه می‌شود تا کل فاصله ستون‌های ماتریس (فاصله بین لبه‌های یکسان ستون‌های مختلف) تعیین شود. پیش‌فرض: 0.

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

نوع فاصله افقی بین ستون‌های یک ماتریس؛ واحدهای فاصله افقی می‌توانند ems یا points باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)

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

نوع فاصله افقی بین ستون‌های یک ماتریس؛ واحدهای فاصله افقی می‌توانند ems یا points باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)

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

مقدار فاصله افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule برابر 3 (\"Exactly\") باشد، واحد به عنوان twips (1/20 ام نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان تعداد گام‌های 0.5 em تفسیر می‌شود. در موارد دیگر نادیده گرفته می‌شود. پیش‌فرض: 0

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

مقدار فاصله افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule برابر 3 (\"Exactly\") باشد، واحد به عنوان twips (1/20 ام نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان تعداد گام‌های 0.5 em تفسیر می‌شود. در موارد دیگر نادیده گرفته می‌شود. پیش‌فرض: 0

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

نوع فاصله عمودی بین ردیف‌های یک ماتریس؛ واحدهای فاصله عمودی می‌توانند خطوط یا نقاط باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)

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

نوع فاصله عمودی بین ردیف‌های یک ماتریس؛ واحدهای فاصله عمودی می‌توانند خطوط یا نقاط باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)

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

مقدار فاصله عمودی بین ردیف‌های یک ماتریس؛ اگر RowGapRule برابر 3 (\"Exactly\") باشد، واحد به عنوان twips (1/20 ام نقطه) تفسیر می‌شود. اگر RowGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان نصف خطوط تفسیر می‌شود. پیش‌فرض: 0

--------------------

> ```
> مثال:
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

مقدار فاصله عمودی بین ردیف‌های یک ماتریس؛ اگر RowGapRule برابر 3 (\"Exactly\") باشد، واحد به عنوان twips (1/20 ام نقطه) تفسیر می‌شود. اگر RowGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان نصف خطوط تفسیر می‌شود. پیش‌فرض: 0

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
| columnIndex | int | اندیس صفر-مبنا برای ستون |
**بازگشت:**
int - تراز افقی ستون مشخص‌شده

### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

تنظیم تراز افقی ستون مشخص‌شده

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | int | اندیس صفر-مبنا برای ستون |
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
| columnIndex | int | اندیس اولین ستونی که می‌خواهید ترازشان را تنظیم کنید |
| columnsCount | long | تعداد ستون‌هایی که می‌خواهید ترازشان را مشخص کنید |
| val | int | مقدار جدید تراز افقی ستون مشخص‌شده |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

درج یک ردیف جدید قبل از ردیف مشخص‌شده. ابتدا تمام عناصر ردیف جدید null هستند.

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
| rowIndex | int | اندیس ردیفی که قبل از آن ردیف جدیدی درج می‌شود |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

درج یک ردیف جدید پس از ردیف مشخص‌شده. ابتدا تمام عناصر ردیف جدید null هستند.

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
| rowIndex | int | اندیس ردیفی که پس از آن ردیف جدیدی درج می‌شود |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

حذف ردیف مشخص‌شده

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
| rowIndex | int | اندیس صفر-مبنا برای ردیفی که می‌خواهید حذف کنید. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

درج یک ستون جدید قبل از ستون مشخص‌شده. ابتدا تمام عناصر ستون جدید null هستند.

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
| columnIndex | int | اندیس ستونی که قبل از آن ستون جدیدی درج می‌شود |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

درج یک ستون جدید پس از ستون مشخص‌شده. ابتدا تمام عناصر ستون جدید null هستند.

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
| columnIndex | int | اندیس ستونی که پس از آن ستون جدیدی درج می‌شود |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

حذف ستون مشخص‌شده

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
| columnIndex | int | اندیس صفر-مبنا برای ستونی که می‌خواهید حذف کنید. |