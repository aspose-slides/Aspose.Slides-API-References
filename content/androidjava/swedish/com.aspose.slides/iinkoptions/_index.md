---
title: IInkOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Provides options that control the look of Ink objects in exported document.
type: docs
url: /sv/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

Tillhandahåller alternativ som styr utseendet på Ink-objekt i exporterade dokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHideInk()](#getHideInk--) | Visar eller döljer Ink-element i exporterade dokumentet. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Visar eller döljer Ink-element i exporterade dokumentet. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Använder ROP-operation eller Opacity för rendering av pensel. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Använder ROP-operation eller Opacity för rendering av pensel. |

### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
```

Visar eller döljer Ink-element i exporterade dokumentet.

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

Standardvärdet är false.

**Returnerar:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public abstract void setHideInk(boolean value)
```

Visar eller döljer Ink-element i exporterade dokumentet.

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

Standardvärdet är false.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public abstract boolean getInterpretMaskOpAsOpacity()
```

Använder ROP-operation eller Opacity för rendering av pensel.

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

Standardvärdet är true.

**Returnerar:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```

Använder ROP-operation eller Opacity för rendering av pensel.

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

Standardvärdet är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |