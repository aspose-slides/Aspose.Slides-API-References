---
title: PdfImportOptions
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά τις επιλογές εισαγωγής PDF
type: docs
url: /el/com.aspose.slides/pdfimportoptions/
---
**Κληρονομικότητα:**
java.lang.Object
```
public class PdfImportOptions
```

Αναπαριστά τις επιλογές εισαγωγής PDF
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | Καθορίζει αν εντοπίζονται πίνακες κατά την εισαγωγή αρχείου pdf. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | Καθορίζει αν εντοπίζονται πίνακες κατά την εισαγωγή αρχείου pdf. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


Καθορίζει αν εντοπίζονται πίνακες κατά την εισαγωγή αρχείου pdf.

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
>          // ορισμός ανίχνευσης πινάκων
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```


Καθορίζει αν εντοπίζονται πίνακες κατά την εισαγωγή αρχείου pdf.

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
>          // ορισμός ανίχνευσης πινάκων
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |