---
title: InkOptions
second_title: Aspose.Slides dla Java – odniesienie API
description: Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie.
type: docs
url: /pl/com.aspose.slides/inkoptions/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie.
## Metody

| Metoda | Opis |
| --- | --- |
| [getHideInk()](#getHideInk--) | Pokazuje lub ukrywa elementy Ink w wyeksportowanym dokumencie. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Pokazuje lub ukrywa elementy Ink w wyeksportowanym dokumencie. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Używa operacji ROP lub przezroczystości do renderowania pędzla. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Używa operacji ROP lub przezroczystości do renderowania pędzla. |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
```


Pokazuje lub ukrywa elementy Ink w wyeksportowanym dokumencie.

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

Domyślna wartość to false.

**Zwraca:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
```


Pokazuje lub ukrywa elementy Ink w wyeksportowanym dokumencie.

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

Domyślna wartość to false.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```


Używa operacji ROP lub przezroczystości do renderowania pędzla.

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

Domyślna wartość to true.

**Zwraca:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```


Używa operacji ROP lub przezroczystości do renderowania pędzla.

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

Domyślna wartość to true.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |