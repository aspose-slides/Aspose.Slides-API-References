---
title: PdfImportOptions
second_title: Aspose.Slides Androidra a Java API hivatkozáson keresztül
description: A PDF importálási beállításokat ábrázolja
type: docs
url: /hu/com.aspose.slides/pdfimportoptions/
---
**Öröklés:**
java.lang.Object
```
public class PdfImportOptions
```

A PDF importálási beállításokat ábrázolja
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | Meghatározza, hogy a PDF-fájl importálása során detektálja-e a táblázatokat. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | Meghatározza, hogy a PDF-fájl importálása során detektálja-e a táblázatokat. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


Meghatározza, hogy a PDF-fájl importálása során detektálja-e a táblázatokat.

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
>          // táblák detektálásának beállítása
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```


Meghatározza, hogy a PDF-fájl importálása során detektálja-e a táblázatokat.

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
>          // táblák detektálásának beállítása
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |