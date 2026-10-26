---
title: SpreadsheetOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: گزینه‌هایی را که می‌توان برای تعیین رفتارهای اضافی صفحات گسترده استفاده کرد، نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/spreadsheetoptions/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

گزینه‌هایی را که می‌توان برای تعیین رفتارهای اضافی صفحات گسترده استفاده کرد، توصیف می‌کند.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | یک نمونه جدید از کلاس [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | اطلاعات فرهنگ ترجیحی را برای محاسبه برخی توابع که برای استفاده با زبان‌هایی که از مجموعه کاراکترهای دو بایتی (DBCS) استفاده می‌کنند، دریافت یا تنظیم می‌کند. |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | اطلاعات فرهنگ ترجیحی را برای محاسبه برخی توابع که برای استفاده با زبان‌هایی که از مجموعه کاراکترهای دو بایتی (DBCS) استفاده می‌کنند، دریافت یا تنظیم می‌کند. |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | اگر منبع داده برای نمودار یک کتاب‌کار خارجی باشد و در دسترس نباشد، از کش نمودار بازیابی خواهد شد. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | اگر منبع داده برای نمودار یک کتاب‌کار خارجی باشد و در دسترس نباشد، از کش نمودار بازیابی خواهد شد. |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```

یک نمونه جدید از کلاس [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) ایجاد می‌کند.

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```

اطلاعات فرهنگ ترجیحی را برای محاسبه برخی توابع که برای استفاده با زبان‌هایی که از مجموعه کاراکترهای دو بایتی (DBCS) استفاده می‌کنند، دریافت یا تنظیم می‌کند.

**بازگشت:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```

اطلاعات فرهنگ ترجیحی را برای محاسبه برخی توابع که برای استفاده با زبان‌هایی که از مجموعه کاراکترهای دو بایتی (DBCS) استفاده می‌کنند، دریافت یا تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```

اگر منبع داده برای نمودار یک کتاب‌کار خارجی باشد و در دسترس نباشد، از کش نمودار بازیابی خواهد شد.

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```


**بازگشت:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public final void setRecoverWorkbookFromChartCache(boolean value)
```

اگر منبع داده برای نمودار یک کتاب‌کار خارجی باشد و در دسترس نباشد، از کش نمودار بازیابی خواهد شد.

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |