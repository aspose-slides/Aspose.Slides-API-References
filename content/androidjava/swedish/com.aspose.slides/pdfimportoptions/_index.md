---
title: PdfImportOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar PDF-importalternativen
type: docs
url: /sv/com.aspose.slides/pdfimportoptions/
---
**Arv:**
java.lang.Object
```
public class PdfImportOptions
```

Representerar PDF-importalternativen
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | Avgör om tabeller ska upptäckas vid import av PDF-fil. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | Avgör om tabeller ska upptäckas vid import av PDF-fil. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


Avgör om tabeller ska upptäckas vid import av PDF-fil.

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
>          // sätt att upptäcka tabeller
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```


Avgör om tabeller ska upptäckas vid import av PDF-fil.

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
>          // aktivera upptäckt av tabeller
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |