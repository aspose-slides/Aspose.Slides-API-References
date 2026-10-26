---
title: IInkOptions
second_title: Aspose.Slides for Java API Reference
description: Fournit des options qui contrôlent l’apparence des objets Ink dans le document exporté.
type: docs
url: /fr/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

Fournit des options qui contrôlent l’apparence des objets Ink dans le document exporté.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHideInk()](#getHideInk--) | Affiche ou masque les éléments Ink dans le document exporté. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Affiche ou masque les éléments Ink dans le document exporté. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Utilise l’opération ROP ou l’opacité pour le rendu du pinceau. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Utilise l’opération ROP ou l’opacité pour le rendu du pinceau. |
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

Valeur par défaut : false.

**Renvoie :**  
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public abstract void setHideInk(boolean value)
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

Valeur par défaut : false.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public abstract boolean getInterpretMaskOpAsOpacity()
```


Utilise l’opération ROP ou l’opacité pour le rendu du pinceau.

--------------------

> ```
> L'exemple suivant montre comment configurer l'utilisation de ROP pour l'exportation des éléments Ink :
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

Valeur par défaut : true.

**Renvoie :**  
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```


Utilise l’opération ROP ou l’opacité pour le rendu du pinceau.

--------------------

> ```
> L'exemple suivant montre comment configurer l'utilisation de ROP pour l'exportation des éléments Ink :
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

Valeur par défaut : true.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |