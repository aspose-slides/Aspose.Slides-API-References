---
title: IInkOptions
second_title: Aspose.Slides for Java API Reference
description: Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen.
type: docs
url: /nl/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHideInk()](#getHideInk--) | Toont of verbergt Ink-elementen in het geëxporteerde document. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Toont of verbergt Ink-elementen in het geëxporteerde document. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Gebruikt ROP-bewerking of Doorzichtigheid voor het renderen van de penseel. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Gebruikt ROP-bewerking of Doorzichtigheid voor het renderen van de penseel. |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
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

**Retour:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public abstract void setHideInk(boolean value)
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public abstract boolean getInterpretMaskOpAsOpacity()
```


Gebruikt ROP-bewerking of Doorzichtigheid voor het renderen van de penseel.

--------------------

> ```
> Volgend voorbeeld toont hoe u ROP instelt voor het exporteren van Ink-elementen:
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

**Retour:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```


Gebruikt ROP-bewerking of Doorzichtigheid voor het renderen van de penseel.

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

Standaardwaarde is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |