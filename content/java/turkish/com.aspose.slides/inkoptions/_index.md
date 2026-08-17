---
title: InkOptions
second_title: Aspose.Slides for Java API Referansı
description: İhrac edilen belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar.
type: docs
url: /tr/com.aspose.slides/inkoptions/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

İhrac edilen belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar.
## Methods

| Method | Description |
| --- | --- |
| [getHideInk()](#getHideInk--) | İhrac edilen belgede Ink öğelerini gösterir veya gizler. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | İhrac edilen belgede Ink öğelerini gösterir veya gizler. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Fırçayı renderlemek için ROP işlemi veya Opacity kullanır. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Fırçayı renderlemek için ROP işlemi veya Opacity kullanır. |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
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

**Returns:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
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
public final boolean getInterpretMaskOpAsOpacity()
```


Fırçayı renderlemek için ROP işlemi veya Opacity kullanır.

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

Varsayılan değer true'tur.

**Returns:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```


Fırçayı renderlemek için ROP işlemi veya Opacity kullanır.

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

Varsayılan değer true'tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |