---
title: IInkOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Proporciona opciones que controlan el aspecto de los objetos Ink en el documento exportado.
type: docs
url: /es/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

Proporciona opciones que controlan el aspecto de los objetos Ink en el documento exportado.
## Métodos

| Método | Descripción |
| --- | --- |
| [getHideInk()](#getHideInk--) | Muestra u oculta los elementos Ink en el documento exportado. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Muestra u oculta los elementos Ink en el documento exportado. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Utiliza la operación ROP u Opacidad para renderizar el pincel. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Utiliza la operación ROP u Opacidad para renderizar el pincel. |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
```

Muestra u oculta los elementos Ink en el documento exportado.

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

El valor predeterminado es false.

**Devuelve:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public abstract void setHideInk(boolean value)
```

Muestra u oculta los elementos Ink en el documento exportado.

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

El valor predeterminado es false.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public abstract boolean getInterpretMaskOpAsOpacity()
```

Utiliza la operación ROP u Opacidad para renderizar el pincel.

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

El valor predeterminado es true.

**Devuelve:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```

Utiliza la operación ROP u Opacidad para renderizar el pincel.

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

El valor predeterminado es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |