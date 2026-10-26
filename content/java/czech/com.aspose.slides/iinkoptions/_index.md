---
title: IInkOptions
second_title: Aspose.Slides for Java API Reference
description: Poskytuje možnosti, které řídí vzhled Ink objektů v exportovaném dokumentu.
type: docs
url: /cs/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

Poskytuje možnosti, které řídí vzhled Ink objektů v exportovaném dokumentu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHideInk()](#getHideInk--) | Zobrazí nebo skryje Ink prvky v exportovaném dokumentu. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Zobrazí nebo skryje Ink prvky v exportovaném dokumentu. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Používá operaci ROP nebo opacity pro vykreslení štětce. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Používá operaci ROP nebo opacity pro vykreslení štětce. |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
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
public abstract void setHideInk(boolean value)
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
public abstract boolean getInterpretMaskOpAsOpacity()
```

Používá operaci ROP nebo opacity pro vykreslení štětce.

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

Výchozí hodnota je true.

**Vrací:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```

Používá operaci ROP nebo opacity pro vykreslení štětce.

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

Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |