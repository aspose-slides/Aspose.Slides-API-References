---
title: PdfImportOptions
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
description: Reprezentuje opcje importu PDF
type: docs
url: /pl/com.aspose.slides/pdfimportoptions/
---
**Dziedziczenie:**  
java.lang.Object  
```
public class PdfImportOptions
```

Represents the PDF import options  
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | Określa, czy wykrywać tabele podczas importowania pliku PDF. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | Określa, czy wykrywać tabele podczas importowania pliku PDF. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```

### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```

Określa, czy wykrywać tabele podczas importowania pliku PDF.

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
>          // ustaw wykrywanie tabel
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**  
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```

Określa, czy wykrywać tabele podczas importowania pliku PDF.

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
>          // ustaw wykrywanie tabel
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
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |