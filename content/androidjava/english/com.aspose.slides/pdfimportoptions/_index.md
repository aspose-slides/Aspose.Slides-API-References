---
title: PdfImportOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the PDF import options
type: docs
url: /com.aspose.slides/pdfimportoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfImportOptions
```

Represents the PDF import options
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | Determines whether detect tables when importing pdf file. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | Determines whether detect tables when importing pdf file. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


Determines whether detect tables when importing pdf file.

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
>          // set detecting tables
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```


Determines whether detect tables when importing pdf file.

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
>          // set detecting tables
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

