---
title: IInkOptions
second_title: Aspose.Slides Android için Java API Referansı
description: Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar.
type: docs
url: /tr/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar.
## Metotlar

| Method | Description |
| --- | --- |
| [getHideInk()](#getHideInk--) | Dışa aktarılan belgede Ink öğelerini gösterir veya gizler. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Dışa aktarılan belgede Ink öğelerini gösterir veya gizler. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Fırça oluşturulurken ROP işlemi veya Opaklık kullanılır. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Fırça oluşturulurken ROP işlemi veya Opaklık kullanılır. |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
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
public abstract void setHideInk(boolean value)
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
public abstract boolean getInterpretMaskOpAsOpacity()
```


Fırça oluşturulurken ROP işlemi veya Opaklık kullanılır.

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

Varsayılan değer doğrudur.

**Döndürür:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```


Fırça oluşturulurken ROP işlemi veya Opaklık kullanılır.

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

Varsayılan değer doğrudur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |