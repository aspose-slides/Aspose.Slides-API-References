---
title: PdfImportOptions
second_title: Referensi API Java Aspose.Slides untuk Android
description: Merepresentasikan opsi impor PDF
type: docs
url: /id/com.aspose.slides/pdfimportoptions/
---
**Pewarisan:**
java.lang.Object
```
public class PdfImportOptions
```

Merepresentasikan opsi impor PDF
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | Menentukan apakah mendeteksi tabel saat mengimpor file PDF. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | Menentukan apakah mendeteksi tabel saat mengimpor file PDF. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


Menentukan apakah mendeteksi tabel saat mengimpor file PDF.

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
>          // atur deteksi tabel
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```


Menentukan apakah mendeteksi tabel saat mengimpor file PDF.

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
>          // atur deteksi tabel
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |