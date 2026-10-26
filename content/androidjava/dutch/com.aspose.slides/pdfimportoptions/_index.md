---
title: PdfImportOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Geeft de PDF-importopties weer
type: docs
url: /nl/com.aspose.slides/pdfimportoptions/
---
**Erfenis:**
java.lang.Object
```
public class PdfImportOptions
```

Geeft de PDF-importopties weer
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | Bepaalt of tabellen worden gedetecteerd bij het importeren van een pdf-bestand. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | Bepaalt of tabellen worden gedetecteerd bij het importeren van een pdf-bestand. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


Bepaalt of tabellen worden gedetecteerd bij het importeren van een pdf-bestand.

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
>          // zet detectie van tabellen
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```


Bepaalt of tabellen worden gedetecteerd bij het importeren van een pdf-bestand.

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
>          // zet detectie van tabellen
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |