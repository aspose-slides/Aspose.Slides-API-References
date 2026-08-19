---
title: PdfImportOptions
second_title: Aspose.Slides برای Java مرجع API
description: نمایانگر گزینه‌های واردات PDF
type: docs
url: /fa/com.aspose.slides/pdfimportoptions/
---
**ارث‌بری:**
java.lang.Object
``` 
public class PdfImportOptions
```

نمایانگر گزینه‌های واردات PDF
## سازندگان

| سازنده | توضیح |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | تشخیص می‌دهد آیا جداول هنگام وارد کردن فایل PDF شناسایی شوند. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | تشخیص می‌دهد آیا جداول هنگام وارد کردن فایل PDF شناسایی شوند. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```

### getDetectTables() {#getDetectTables--}
``` 
public final boolean getDetectTables()
```

تشخیص می‌دهد آیا جداول هنگام وارد کردن فایل PDF شناسایی شوند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      {
>          // تنظیم تشخیص جداول
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**باز می‌گرداند:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
``` 
public final void setDetectTables(boolean value)
```

تشخیص می‌دهد آیا جداول هنگام وارد کردن فایل PDF شناسایی شوند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      {
>          // تنظیم تشخیص جداول
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |