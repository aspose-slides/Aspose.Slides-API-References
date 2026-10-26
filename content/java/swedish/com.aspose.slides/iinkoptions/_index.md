---
title: IInkOptions
second_title: Aspose.Slides för Java API-referens
description: Tillhandahåller alternativ som styr utseendet på Ink-objekt i exporterade dokument.
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
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Använder ROP-operation eller Opacitet för att rendera penseln. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Använder ROP-operation eller Opacitet för att rendera penseln. |
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
Standardvärdet är falskt.

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
Standardvärdet är falskt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public abstract boolean getInterpretMaskOpAsOpacity()
```


Använder ROP-operation eller Opacitet för att rendera penseln.

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
Standardvärdet är sant.

**Returnerar:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```


Använder ROP-operation eller Opacitet för att rendera penseln.

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
Standardvärdet är sant.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |