---
title: IInkOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté.
type: docs
url: /fr/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHideInk()](#getHideInk--) | Affiche ou masque les éléments Ink dans le document exporté. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Affiche ou masque les éléments Ink dans le document exporté. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Utilise l'opération ROP ou l'opacité pour le rendu du pinceau. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Utilise l'opération ROP ou l'opacité pour le rendu du pinceau. |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
```

Affiche ou masque les éléments Ink dans le document exporté.

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

Default value is false.

**Returns:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public abstract void setHideInk(boolean value)
```


Shows or hides Ink elements in exported document.

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

Default value is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public abstract boolean getInterpretMaskOpAsOpacity()
```
Uses ROP operation or Opacity for rendering brush.

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

Default value is true.

**Returns:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)

Uses ROP operation or Opacity for rendering brush.

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

La valeur par défaut est true.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |