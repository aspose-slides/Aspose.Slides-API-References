---
title: CellInvalidFormulaException
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: استثنایی که هنگام نادرست بودن یا عدم تجزیه‌ی یک فرمول محاسبه‌شده رخ می‌دهد.
type: docs
url: /fa/com.aspose.slides/cellinvalidformulaexception/
---
**ارث‌بری:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

استثنایی که هنگام نادرست بودن یا عدم تجزیه‌ی یک فرمول محاسبه‌شده رخ می‌دهد.
## سازندگان

| سازنده | توضیح |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | یک نمونه جدید از کلاس [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) را ایجاد می‌کند. |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | یک نمونه جدید از کلاس [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) را با پیام خطای مشخص شده ایجاد می‌کند. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | یک نمونه جدید از کلاس [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) را با پیام خطای مشخص شده و مرجعی به استثنای داخلی که عامل این استثنا است، ایجاد می‌کند. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | یک نمونه جدید از کلاس [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) را با پیام خطای مشخص شده و مرجع سلولی که فرمول نادرست را شامل می‌شود، ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getReference()](#getReference--) | مرجعی به سلولی که فرمول نادرست را شامل می‌شود را دریافت می‌کند. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```


یک نمونه جدید از کلاس [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) را ایجاد می‌کند.

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```


یک نمونه جدید از کلاس [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) را با پیام خطای مشخص شده ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| message | java.lang.String | رشته‌ای که خطا را توصیف می‌کند. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```


یک نمونه جدید از کلاس [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) را با پیام خطای مشخص شده و مرجعی به استثنای داخلی که عامل این استثنا است، ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| message | java.lang.String | رشته‌ای که خطا را توصیف می‌کند. |
| innerException | java.lang.RuntimeException | استثنایی که عامل استثنای جاری است. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```


یک نمونه جدید از کلاس [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) را با پیام خطای مشخص شده و مرجع سلولی که فرمول نادرست را شامل می‌شود، ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| message | java.lang.String | رشته‌ای که خطا را توصیف می‌کند. |
| reference | java.lang.String | رشته‌ای که مرجع به استثنای داخلی را توصیف می‌کند. |

### getReference() {#getReference--}
```
public final String getReference()
```


مرجعی به سلولی که فرمول نادرست را شامل می‌شود را دریافت می‌کند.

**بازگشت:**
java.lang.String