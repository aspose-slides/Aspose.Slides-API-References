---
title: PdfImportOptions
second_title: Aspose.Slides Java API referencia
description: A PDF importálási beállításokat képviseli
type: docs
url: /hu/com.aspose.slides/pdfimportoptions/
---
**Öröklődés:**
java.lang.Object
```
public class PdfImportOptions
```

A PDF importálási beállításokat képviseli

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | Megállapítja, hogy a PDF fájl importálása során táblázatokat észleljen-e. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | Megállapítja, hogy a PDF fájl importálása során táblázatokat észleljen-e. |

### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```

### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```

Megállapítja, hogy a PDF fájl importálása során táblázatokat észleljen-e.

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
>          // táblák észlelésének beállítása
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

Megállapítja, hogy a PDF fájl importálása során táblázatokat észleljen-e.

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
>          // táblák észlelésének beállítása
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