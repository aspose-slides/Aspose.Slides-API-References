---
title: CellCircularReferenceException
second_title: مرجع API Aspose.Slides برای جاوا
description: استثنایی که هنگام شناسایی یک یا چند ارجاع دایره‌ای که در آن فرمول به سلول خود به‌صورت مستقیم یا غیرمستقیم ارجاع می‌دهد، پرتاب می‌شود.
type: docs
url: /fa/com.aspose.slides/cellcircularreferenceexception/
---
**ارث‌بری:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

استثنایی که زمانی پرتاب می‌شود که یک یا چند ارجاع دایره‌ای شناسایی می‌شود که در آن فرمول به سلول خود به‌صورت مستقیم یا غیرمستقیم ارجاع می‌دهد.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | یک نمونه جدید از کلاس [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) را مقداردهی می‌کند. |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | یک نمونه جدید از کلاس [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) را با پیغام خطای مشخص مقداردهی می‌کند. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | یک نمونه جدید از کلاس [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) را با پیغام خطای مشخص و ارجاعی به استثنای داخلی که دلیل این استثنا است مقداردهی می‌کند. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | یک نمونه جدید از کلاس [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) را با پیغام خطای مشخص و ارجاع سلول دایره‌ای مقداردهی می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getReference()](#getReference--) | یک ارجاع سلول دایره‌ای را دریافت می‌کند. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```


یک نمونه جدید از کلاس [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) را مقداردهی می‌کند.

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```


یک نمونه جدید از کلاس [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) را با پیغام خطای مشخص مقداردهی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| message | java.lang.String | رشته‌ای که خطا را توصیف می‌کند. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```


یک نمونه جدید از کلاس [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) را با پیغام خطای مشخص و ارجاعی به استثنای داخلی که دلیل این استثنا است مقداردهی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| message | java.lang.String | رشته‌ای که خطا را توصیف می‌کند. |
| innerException | java.lang.RuntimeException | استثنایی که دلیل استثنای جاری است. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```


یک نمونه جدید از کلاس [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) را با پیغام خطای مشخص و ارجاع سلول دایره‌ای مقداردهی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| message | java.lang.String | رشته‌ای که خطا را توصیف می‌کند. |
| reference | java.lang.String | یک ارجاع سلول دایره‌ای. |

### getReference() {#getReference--}
```
public final String getReference()
```


یک ارجاع سلول دایره‌ای را دریافت می‌کند.

**بازگشت:**
java.lang.String