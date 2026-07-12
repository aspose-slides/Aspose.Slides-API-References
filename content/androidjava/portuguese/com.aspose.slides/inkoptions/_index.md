---
title: InkOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Fornece opções que controlam a aparência de objetos Ink em documentos exportados.
type: docs
url: /pt/com.aspose.slides/inkoptions/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

Fornece opções que controlam a aparência de objetos Ink em documentos exportados.
## Métodos

| Método | Descrição |
| --- | --- |
| [getHideInk()](#getHideInk--) | Mostra ou oculta elementos Ink em documentos exportados. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Mostra ou oculta elementos Ink em documentos exportados. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Usa operação ROP ou Opacidade para renderizar o pincel. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Usa operação ROP ou Opacidade para renderizar o pincel. |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
```


Mostra ou oculta elementos Ink em documentos exportados.

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

Valor padrão é false.

**Retorna:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
```


Mostra ou oculta elementos Ink em documentos exportados.

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

Valor padrão é false.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```


Usa operação ROP ou Opacidade para renderizar o pincel.

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

Valor padrão é true.

**Retorna:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```


Usa operação ROP ou Opacidade para renderizar o pincel.

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

Valor padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |