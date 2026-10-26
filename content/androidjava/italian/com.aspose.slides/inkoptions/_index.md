---
title: InkOptions
second_title: Aspose.Slides per Android via Riferimento API Java
description: Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato.
type: docs
url: /it/com.aspose.slides/inkoptions/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHideInk()](#getHideInk--) | Mostra o nasconde gli elementi Ink nel documento esportato. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Mostra o nasconde gli elementi Ink nel documento esportato. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Utilizza l'operazione ROP o l'opacità per il rendering del pennello. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Utilizza l'operazione ROP o l'opacità per il rendering del pennello. |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
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
public final void setHideInk(boolean value)
```


Mostra o nasconde gli elementi Ink nel documento esportato.

--------------------

> ```
> Il prossimo esempio dimostra come nascondere gli elementi Ink nel documento PDF esportato:
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
public final boolean getInterpretMaskOpAsOpacity()
```


Utilizza l'operazione ROP o l'opacità per il rendering del pennello.

--------------------

> ```
> Il prossimo esempio dimostra come impostare l'uso di ROP per esportare gli elementi Ink:
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
public final void setInterpretMaskOpAsOpacity(boolean value)
```


Utilizza l'operazione ROP o l'opacità per il rendering del pennello.

--------------------

> ```
> Il prossimo esempio dimostra come impostare l'uso di ROP per esportare gli elementi Ink:
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