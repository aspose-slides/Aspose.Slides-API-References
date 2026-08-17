---
title: IInkOptions
second_title: Aspose.Slides for Java API Reference
description: İhrac edilen belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar.
type: docs
url: /tr/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

İhrac edilen belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHideInk()](#getHideInk--) | İhrac edilen belgede Ink öğelerini gösterir veya gizler. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | İhrac edilen belgede Ink öğelerini gösterir veya gizler. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Fırçanın işlenmesi için ROP işlemi veya Opaklık kullanır. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Fırçanın işlenmesi için ROP işlemi veya Opaklık kullanır. |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
```


İhrac edilen belgede Ink öğelerini gösterir veya gizler.

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
public abstract void setHideInk(boolean value)
```


İhrac edilen belgede Ink öğelerini gösterir veya gizler.

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
public abstract boolean getInterpretMaskOpAsOpacity()
```


Fırçanın işlenmesi için ROP işlemi veya Opaklık kullanır.

--------------------

> ```
> Next example demonstrates how to set using ROP for exporting Ink elements:
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

Varsayılan değer true'tur.

**Döndürür:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```


Fırçanın işlenmesi için ROP işlemi veya Opaklık kullanır.

--------------------

> ```
> Next example demonstrates how to set using ROP for exporting Ink elements:
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

Varsayılan değer true'tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |