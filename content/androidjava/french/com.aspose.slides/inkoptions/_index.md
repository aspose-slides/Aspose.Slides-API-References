---
title: InkOptions
second_title: Aspose.Slides pour Android via la référence API Java
description: Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté.
type: docs
url: /fr/com.aspose.slides/inkoptions/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
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
public final boolean getHideInk()
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
public final void setHideInk(boolean value)
```

Affiche ou masque les éléments Ink dans le document exporté.

--------------------

> ```
> Exemple suivant montre comment masquer les éléments Ink dans le document PDF exporté :
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

Valeur par défaut est false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```

Utilise l'opération ROP ou l'opacité pour le rendu du pinceau.

--------------------

> ```
> L'exemple suivant montre comment définir l'utilisation de ROP pour l'exportation des éléments Ink :
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

Valeur par défaut est true.

**Returns:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)


Utilise l'opération ROP ou l'opacité pour le rendu du pinceau.

--------------------

> ```
> L'exemple suivant montre comment définir l'utilisation de ROP pour l'exportation des éléments Ink :
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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |