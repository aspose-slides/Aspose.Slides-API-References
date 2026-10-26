---
title: InkOptions
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern.
type: docs
url: /de/com.aspose.slides/inkoptions/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHideInk()](#getHideInk--) | Zeigt Ink-Elemente im exportierten Dokument an oder blendet sie aus. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Zeigt Ink-Elemente im exportierten Dokument an oder blendet sie aus. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Verwendet ROP-Operation oder Opazität für das Rendern des Pinsels. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Verwendet ROP-Operation oder Opazität für das Rendern des Pinsels. |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
```


Zeigt Ink-Elemente im exportierten Dokument an oder blendet sie aus.

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

Der Standardwert ist false.

**Rückgabewert:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
```


Zeigt Ink-Elemente im exportierten Dokument an oder blendet sie aus.

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

Der Standardwert ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```


Verwendet ROP-Operation oder Opazität für das Rendern des Pinsels.

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

Der Standardwert ist true.

**Rückgabewert:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```


Verwendet ROP-Operation oder Opazität für das Rendern des Pinsels.

--------------------

> ```
> Das nächste Beispiel zeigt, wie man ROP beim Exportieren von Ink-Elementen verwendet:
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

Der Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |