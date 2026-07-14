---
title: PdfImportOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر گزینه‌های وارد کردن PDF
type: docs
url: /fa/com.aspose.slides/pdfimportoptions/
---
**وراثت:**
java.lang.Object
```
public class PdfImportOptions
```

نمایانگر گزینه‌های وارد کردن PDF
## سازنده‌ها

| Constructor | Description |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## متدها

| Method | Description |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | مشخص می‌کند که آیا جداول هنگام وارد کردن فایل PDF شناسایی شوند یا خیر. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | مشخص می‌کند که آیا جداول هنگام وارد کردن فایل PDF شناسایی شوند یا خیر. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


مشخص می‌کند که آیا جداول هنگام وارد کردن فایل PDF شناسایی شوند یا خیر.

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


**بازگشت:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```


مشخص می‌کند که آیا جداول هنگام وارد کردن فایل PDF شناسایی شوند یا خیر.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |