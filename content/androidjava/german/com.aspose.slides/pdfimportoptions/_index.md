---
title: PdfImportOptions
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt die PDF-Importoptionen dar
type: docs
url: /de/com.aspose.slides/pdfimportoptions/
---
**Vererbung:**
java.lang.Object
```
public class PdfImportOptions
```

Stellt die PDF-Importoptionen dar
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | Bestimmt, ob Tabellen beim Importieren einer PDF-Datei erkannt werden. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | Bestimmt, ob Tabellen beim Importieren einer PDF-Datei erkannt werden. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


Bestimmt, ob Tabellen beim Importieren einer PDF-Datei erkannt werden.

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
>          // Tabellenerkennung aktivieren
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabewert:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```


Bestimmt, ob Tabellen beim Importieren einer PDF-Datei erkannt werden.

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
>          // Tabellenerkennung aktivieren
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |