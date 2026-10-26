---
title: CellInvalidReferenceException
second_title: مرجع API جاوا برای Aspose.Slides برای اندروید
description: استثنایی که هنگام مواجهه با یک ارجاع سلول نامعتبر پرتاب می‌شود.
type: docs
url: /fa/com.aspose.slides/cellinvalidreferenceexception/
---
**ارث‌بری:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

استثنایی که هنگام مواجهه با یک ارجاع سلول نامعتبر پرتاب می‌شود.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | یک نمونه جدید از کلاس [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) را مقداردهی اولیه می‌کند. |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | یک نمونه جدید از کلاس [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) را با پیام خطای مشخص مقداردهی اولیه می‌کند. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | یک نمونه جدید از کلاس [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) را با پیام خطای مشخص و یک ارجاع به استثنای داخلی که سبب این استثناست، مقداردهی اولیه می‌کند. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | یک نمونه جدید از کلاس [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) را با پیام خطای مشخص و یک ارجاع سلول نامعتبر، مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getReference()](#getReference--) | یک ارجاع سلول نامعتبر را برمی‌گرداند. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

یک نمونه جدید از کلاس [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) را مقداردهی اولیه می‌کند.

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

یک نمونه جدید از کلاس [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) را با پیام خطای مشخص مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| message | java.lang.String | رشته‌ای که خطا را توصیف می‌کند. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

یک نمونه جدید از کلاس [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) را با پیام خطای مشخص و یک ارجاع به استثنای داخلی که سبب این استثناست، مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| message | java.lang.String | رشته‌ای که خطا را توصیف می‌کند. |
| innerException | java.lang.RuntimeException | استثنایی که سبب استثنای جاری است. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

یک نمونه جدید از کلاس [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) را با پیام خطای مشخص و یک ارجاع سلول نامعتبر، مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| message | java.lang.String | رشته‌ای که خطا را توصیف می‌کند. |
| reference | java.lang.String | یک ارجاع سلول نامعتبر. |

### getReference() {#getReference--}
```
public final String getReference()
```

یک ارجاع سلول نامعتبر را برمی‌گرداند.

**بازگشت:**
java.lang.String