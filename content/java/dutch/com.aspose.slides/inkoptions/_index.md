---
title: InkOptions
second_title: Aspose.Slides voor Java API-referentie
description: Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen.
type: docs
url: /nl/com.aspose.slides/inkoptions/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
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
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Gebruikt ROP-bewerking of Opaciteit voor het renderen van de penseel. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Gebruikt ROP-bewerking of Opaciteit voor het renderen van de penseel. |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
```


Toont of verbergt Ink-elementen in het geëxporteerde document.

--------------------

> ```
> Volgend voorbeeld laat zien hoe Ink-elementen in een geëxporteerd PDF-document verborgen kunnen worden:
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

**Retourwaarde:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
```


Toont of verbergt Ink-elementen in het geëxporteerde document.

--------------------

> ```
> Volgend voorbeeld laat zien hoe Ink-elementen in een geëxporteerd PDF-document verborgen kunnen worden:
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


Gebruikt ROP-bewerking of Opaciteit voor het renderen van de penseel.

--------------------

> ```
> Volgend voorbeeld laat zien hoe ROP wordt ingesteld voor het exporteren van Ink-elementen:
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

**Retourwaarde:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```


Gebruikt ROP-bewerking of Opaciteit voor het renderen van de penseel.

--------------------

> ```
> Volgend voorbeeld laat zien hoe ROP wordt ingesteld voor het exporteren van Ink-elementen:
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