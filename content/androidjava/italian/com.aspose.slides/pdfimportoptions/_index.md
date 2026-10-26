---
title: PdfImportOptions
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta le opzioni di importazione PDF
type: docs
url: /it/com.aspose.slides/pdfimportoptions/
---
**Eredità:**
java.lang.Object
```
public class PdfImportOptions
```

Rappresenta le opzioni di importazione PDF
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | Determina se rilevare tabelle durante l'importazione del file PDF. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | Determina se rilevare tabelle durante l'importazione del file PDF. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


Determina se rilevare tabelle durante l'importazione del file PDF.

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
>          // imposta il rilevamento delle tabelle
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```


Determina se rilevare tabelle durante l'importazione del file PDF.

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
>          // imposta il rilevamento delle tabelle
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |