---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Java API Reference
description: گزینه‌هایی که می‌توانند برای تعیین رفتار اضافی صفحات گسترده استفاده شوند.
type: docs
url: /fa/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

گزینه‌هایی را نشان می‌دهد که می‌توانند برای مشخص کردن رفتارهای اضافی صفحات گسترده استفاده شوند.
## متدها

| متد | توضیح |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | اطلاعات فرهنگ ترجیحی را برای محاسبه برخی توابع که برای استفاده در زبان‌هایی که مجموعه کاراکتر دو بایتی (DBCS) استفاده می‌کنند، دریافت یا تنظیم می‌کند. |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | اطلاعات فرهنگ ترجیحی را برای محاسبه برخی توابع که برای استفاده در زبان‌هایی که مجموعه کاراکتر دو بایتی (DBCS) استفاده می‌کنند، دریافت یا تنظیم می‌کند. |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | اگر منبع داده برای نمودار یک کتاب کار خارجی باشد و در دسترس نباشد، از حافظه پنهان نمودار بازیابی خواهد شد. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | اگر منبع داده برای نمودار یک کتاب کار خارجی باشد و در دسترس نباشد، از حافظه پنهان نمودار بازیابی خواهد شد. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


اطلاعات فرهنگ ترجیحی را برای محاسبه برخی توابع که برای استفاده در زبان‌هایی که مجموعه کاراکتر دو بایتی (DBCS) استفاده می‌کنند، دریافت یا تنظیم می‌کند.

**بازگشت:**  
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


اطلاعات فرهنگ ترجیحی را برای محاسبه برخی توابع که برای استفاده در زبان‌هایی که مجموعه کاراکتر دو بایتی (DBCS) استفاده می‌کنند، دریافت یا تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | java.util.Locale |  |
### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


اگر منبع داده برای نمودار یک کتاب کار خارجی باشد و در دسترس نباشد، از حافظه پنهان نمودار بازیابی خواهد شد.

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
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```


اگر منبع داده برای نمودار یک کتاب کار خارجی باشد و در دسترس نباشد، از حافظه پنهان نمودار بازیابی خواهد شد.

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
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | boolean |  |