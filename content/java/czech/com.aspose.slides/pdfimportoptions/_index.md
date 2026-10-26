---
title: PdfImportOptions
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje možnosti importu PDF
type: docs
url: /cs/com.aspose.slides/pdfimportoptions/
---
**Dědičnost:**
java.lang.Object
```
public class PdfImportOptions
```

Reprezentuje možnosti importu PDF
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | Určuje, zda při importu souboru PDF detekovat tabulky. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | Určuje, zda při importu souboru PDF detekovat tabulky. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


Určuje, zda při importu souboru PDF detekovat tabulky.

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
>          // nastavit detekci tabulek
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```


Určuje, zda při importu souboru PDF detekovat tabulky.

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
>          // nastavit detekci tabulek
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |