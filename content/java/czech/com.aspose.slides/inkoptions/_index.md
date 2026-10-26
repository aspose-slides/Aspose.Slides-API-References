---
title: InkOptions
second_title: Aspose.Slides pro Java API Reference
description: Poskytuje možnosti, které řídí vzhled Ink objektů v exportovaném dokumentu.
type: docs
url: /cs/com.aspose.slides/inkoptions/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

Poskytuje možnosti, které řídí vzhled Ink objektů v exportovaném dokumentu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHideInk()](#getHideInk--) | Zobrazí nebo skryje Ink prvky v exportovaném dokumentu. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Zobrazí nebo skryje Ink prvky v exportovaném dokumentu. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Používá operaci ROP nebo neprůhlednost pro vykreslování štětce. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Používá operaci ROP nebo neprůhlednost pro vykreslování štětce. |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
```

Zobrazí nebo skryje Ink prvky v exportovaném dokumentu.

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

Výchozí hodnota je false.

**Vrací:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
```

Zobrazí nebo skryje Ink prvky v exportovaném dokumentu.

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

Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```

Používá operaci ROP nebo neprůhlednost pro vykreslování štětce.

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

Výchozí hodnota je true.

**Vrací:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```

Používá operaci ROP nebo neprůhlednost pro vykreslování štětce.

--------------------

> ```
> Další příklad ukazuje, jak nastavit použití ROP pro export Ink prvků:
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

Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |