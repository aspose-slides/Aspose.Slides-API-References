---
title: PdfImportOptions
second_title: Aspose.Slides for Android için Java API Referansı
description: PDF içe aktarma seçeneklerini temsil eder
type: docs
url: /tr/com.aspose.slides/pdfimportoptions/
---
**Miras:**
java.lang.Object
```
public class PdfImportOptions
```

PDF içe aktarma seçeneklerini temsil eder
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | PDF dosyası içe aktarılırken tabloların algılanıp algılanmayacağını belirler. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | PDF dosyası içe aktarılırken tabloların algılanıp algılanmayacağını belirler. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```

### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```

PDF dosyası içe aktarılırken tabloların algılanıp algılanmayacağını belirler.

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
>          // tabloların algılanmasını ayarla
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```

PDF dosyası içe aktarılırken tabloların algılanıp algılanmayacağını belirler.

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
>          // tabloların algılanmasını ayarla
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |