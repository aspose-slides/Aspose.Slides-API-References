---
title: InkOptions
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor.
type: docs
url: /id/com.aspose.slides/inkoptions/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getHideInk()](#getHideInk--) | Menampilkan atau menyembunyikan elemen Ink dalam dokumen yang diekspor. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Menampilkan atau menyembunyikan elemen Ink dalam dokumen yang diekspor. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Menggunakan operasi ROP atau Opacity untuk merender kuas. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Menggunakan operasi ROP atau Opacity untuk merender kuas. |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
```

Menampilkan atau menyembunyikan elemen Ink dalam dokumen yang diekspor.

--------------------

> ```
> Next example demonstrates how to hide Ink elements in exported PDF document:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setHideInk(true);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Nilai default adalah false.

**Mengembalikan:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
```

Menampilkan atau menyembunyikan elemen Ink dalam dokumen yang diekspor.

--------------------

> ```
> Next example demonstrates how to hide Ink elements in exported PDF document:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setHideInk(true);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Nilai default adalah false.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```

Menggunakan operasi ROP atau Opacity untuk merender kuas.

--------------------

> ```
> Next example demonstrates how to set using ROP for expotring Ink elements:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setInterpretMaskOpAsOpacity(false);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Nilai default adalah true.

**Mengembalikan:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```

Menggunakan operasi ROP atau Opacity untuk merender kuas.

--------------------

> ```
> Next example demonstrates how to set using ROP for expotring Ink elements:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setInterpretMaskOpAsOpacity(false);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Nilai default adalah true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |