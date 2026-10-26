---
title: IInkOptions
second_title: Aspose.Slides for Java API Reference
description: Fornece opções que controlam a aparência dos objetos Ink no documento exportado.
type: docs
url: /pt/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

Fornece opções que controlam a aparência dos objetos Ink no documento exportado.
## Métodos

| Método | Descrição |
| --- | --- |
| [getHideInk()](#getHideInk--) | Mostra ou oculta elementos Ink no documento exportado. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Mostra ou oculta elementos Ink no documento exportado. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Usa operação ROP ou Opacidade para renderizar o pincel. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Usa operação ROP ou Opacidade para renderizar o pincel. |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
```


Mostra ou oculta elementos Ink no documento exportado.

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

O valor padrão é false.

**Retorna:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public abstract void setHideInk(boolean value)
```


Mostra ou oculta elementos Ink no documento exportado.

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

O valor padrão é false.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public abstract boolean getInterpretMaskOpAsOpacity()
```


Usa operação ROP ou Opacidade para renderizar o pincel.

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

O valor padrão é true.

**Retorna:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```


Usa operação ROP ou Opacidade para renderizar o pincel.

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

O valor padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |