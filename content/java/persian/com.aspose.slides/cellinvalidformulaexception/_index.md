---
title: CellInvalidFormulaException
second_title: مرجع API Aspose.Slides برای جاوا
description: استثنائی که زمانی که یک فرمول محاسبه‌شده صحیح نباشد یا تجزیه نشود، پرتاب می‌شود.
type: docs
url: /fa/com.aspose.slides/cellinvalidformulaexception/
---
**ارث‌بری:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

استثنائی که زمانی که یک فرمول محاسبه‌شده صحیح نباشد یا تجزیه نشود، پرتاب می‌شود.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | یک نمونه جدید از کلاس [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) را مقداردهی اولیه می‌کند. |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | یک نمونه جدید از کلاس [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) را با پیام خطای مشخص مقداردهی اولیه می‌کند. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | یک نمونه جدید از کلاس [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) را با پیام خطای مشخص و مرجعی به استثنای داخلی که دلیل این استثنا است، مقداردهی اولیه می‌کند. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | یک نمونه جدید از کلاس [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) را با پیام خطای مشخص و مرجعی به سلولی که فرمول نامعتبر را شامل می‌شود، مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getReference()](#getReference--) | مرجعی به سلولی که فرمول نامعتبر را شامل می‌شود، برمی‌گرداند. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

یک نمونه جدید از کلاس [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) را مقداردهی اولیه می‌کند.

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

یک نمونه جدید از کلاس [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) را با پیام خطای مشخص مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| message | java.lang.String | رشته‌ای که خطا را توضیح می‌دهد. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

یک نمونه جدید از کلاس [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) را با پیام خطای مشخص و مرجعی به استثنای داخلی که دلیل این استثنا است، مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| message | java.lang.String | رشته‌ای که خطا را توضیح می‌دهد. |
| innerException | java.lang.RuntimeException | استثنایی که دلیل استثنای جاری است. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

یک نمونه جدید از کلاس [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) را با پیام خطای مشخص و مرجعی به سلولی که فرمول نامعتبر را شامل می‌شود، مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| message | java.lang.String | رشته‌ای که خطا را توضیح می‌دهد. |
| reference | java.lang.String | رشته‌ای که مرجعی به استثنای داخلی را توصیف می‌کند. |

### getReference() {#getReference--}
```
public final String getReference()
```

مرجعی به سلولی که فرمول نامعتبر را شامل می‌شود، برمی‌گرداند.

**بازگشت:**
java.lang.String