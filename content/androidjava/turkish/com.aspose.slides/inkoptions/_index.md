---
title: InkOptions
second_title: Aspose.Slides for Android için Java API Referansı
description: Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar.
type: docs
url: /tr/com.aspose.slides/inkoptions/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar.
## Yöntemler

| Method | Açıklama |
| --- | --- |
| [getHideInk()](#getHideInk--) | Dışa aktarılan belgede Ink öğelerini gösterir veya gizler. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Dışa aktarılan belgede Ink öğelerini gösterir veya gizler. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Fırça çiziminde ROP işlemi veya Opacity kullanır. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Fırça çiziminde ROP işlemi veya Opacity kullanır. |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
```


Dışa aktarılan belgede Ink öğelerini gösterir veya gizler.

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

Varsayılan değer false'tur.

**Döndürür:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
```


Dışa aktarılan belgede Ink öğelerini gösterir veya gizler.

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

Varsayılan değer false'tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```


Fırça çiziminde ROP işlemi veya Opacity kullanır.

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

Varsayılan değer true'dur.

**Döndürür:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```


Fırça çiziminde ROP işlemi veya Opacity kullanır.

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

Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |