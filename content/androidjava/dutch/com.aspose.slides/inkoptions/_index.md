---
title: InkOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen.
type: docs
url: /nl/com.aspose.slides/inkoptions/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)  
```
public class InkOptions implements IInkOptions
```

Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHideInk()](#getHideInk--) | Toont of verbergt Ink-elementen in het geëxporteerde document. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Toont of verbergt Ink-elementen in het geëxporteerde document. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Gebruikt ROP-operatie of Opacity voor het renderen van de penseel. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Gebruikt ROP-operatie of Opacity voor het renderen van de penseel. |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
```

Toont of verbergt Ink-elementen in het geëxporteerde document.

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

Standaardwaarde is false.

**Returns:**  
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
```

Toont of verbergt Ink-elementen in het geëxporteerde document.

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

Standaardwaarde is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```

Gebruikt ROP-operatie of Opacity voor het renderen van de penseel.

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

Standaardwaarde is true.

**Returns:**  
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```

Gebruikt ROP-operatie of Opacity voor het renderen van de penseel.

--------------------

> ```
> Volgend voorbeeld toont hoe ROP kan worden gebruikt voor het exporteren van Ink-elementen:
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

Standaardwaarde is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |