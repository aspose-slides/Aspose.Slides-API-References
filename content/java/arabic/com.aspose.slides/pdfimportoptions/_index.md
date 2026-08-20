---
title: PdfImportOptions
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل خيارات استيراد PDF
type: docs
url: /ar/com.aspose.slides/pdfimportoptions/
---
**الوراثة:**  
java.lang.Object  
```
public class PdfImportOptions
```

يمثل خيارات استيراد PDF
## البُنَائِّ

| البنّاء | الوصف |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | يحدد ما إذا كان يتم اكتشاف الجداول عند استيراد ملف PDF. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | يحدد ما إذا كان يتم اكتشاف الجداول عند استيراد ملف PDF. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```

### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```

يحدد ما إذا كان يتم اكتشاف الجداول عند استيراد ملف PDF.

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
>          // ضبط اكتشاف الجداول
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**  
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```

يحدد ما إذا كان يتم اكتشاف الجداول عند استيراد ملف PDF.

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
>          // ضبط اكتشاف الجداول
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |