---
title: IInkOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato.
type: docs
url: /it/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHideInk()](#getHideInk--) | Mostra o nasconde gli elementi Ink nel documento esportato. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Mostra o nasconde gli elementi Ink nel documento esportato. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Utilizza l'operazione ROP o Opacity per il rendering del pennello. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Utilizza l'operazione ROP o Opacity per il rendering del pennello. |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
```


Mostra o nasconde gli elementi Ink nel documento esportato.

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

Il valore predefinito è false.

**Restituisce:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public abstract void setHideInk(boolean value)
```


Mostra o nasconde gli elementi Ink nel documento esportato.

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

Il valore predefinito è false.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public abstract boolean getInterpretMaskOpAsOpacity()
```


Utilizza l'operazione ROP o Opacity per il rendering del pennello.

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

Il valore predefinito è true.

**Restituisce:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```


Utilizza l'operazione ROP o Opacity per il rendering del pennello.

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

Il valore predefinito è true.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |