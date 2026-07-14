---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Android via Java API Reference
description: گزینه‌هایی را نشان می‌دهد که می‌توان برای تعیین رفتارهای اضافی صفحات-گسترده استفاده کرد.
type: docs
url: /fa/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

نمایانگر گزینه‌هایی است که می‌توانند برای تعیین رفتارهای اضافی صفحات-گسترده استفاده شوند.
## متدها

| متد | توضیح |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | اطلاعات فرهنگ ترجیحی را برای محاسبه برخی توابعی که برای زبان‌هایی با مجموعه کاراکتر دوباییتی (DBCS) در نظر گرفته شده‌اند، دریافت یا تنظیم می‌کند. |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | اطلاعات فرهنگ ترجیحی را برای محاسبه برخی توابعی که برای زبان‌هایی با مجموعه کاراکتر دوباییتی (DBCS) در نظر گرفته شده‌اند، دریافت یا تنظیم می‌کند. |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | اگر منبع داده برای نمودار یک دفتر کار خارجی باشد و در دسترس نباشد، از حافظه کش نمودار بازیابی می‌شود. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | اگر منبع داده برای نمودار یک دفتر کار خارجی باشد و در دسترس نباشد، از حافظه کش نمودار بازیابی می‌شود. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


اطلاعات فرهنگ ترجیحی را برای محاسبه برخی توابعی که برای زبان‌هایی که از مجموعه کاراکتر دوباییتی (DBCS) استفاده می‌کنند، دریافت یا تنظیم می‌کند.

**بازگرداندن:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


اطلاعات فرهنگ ترجیحی را برای محاسبه برخی توابعی که برای زبان‌هایی که از مجموعه کاراکتر دوباییتی (DBCS) استفاده می‌کنند، دریافت یا تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


اگر منبع داده برای نمودار یک دفتر کار خارجی باشد و در دسترس نباشد، از حافظه کش نمودار بازیابی می‌شود.

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


**بازگرداندن:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```


اگر منبع داده برای نمودار یک دفتر کار خارجی باشد و در دسترس نباشد، از حافظه کش نمودار بازیابی می‌شود.

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