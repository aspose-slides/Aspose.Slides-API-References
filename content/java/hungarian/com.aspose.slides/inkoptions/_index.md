---
title: InkOptions
second_title: Aspose.Slides Java API referencia
description: Lehetőségeket biztosít az exportált dokumentumban lévő Ink objektumok megjelenésének szabályozásához.
type: docs
url: /hu/com.aspose.slides/inkoptions/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

Lehetőségeket biztosít az exportált dokumentumban lévő Ink objektumok megjelenésének szabályozásához.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getHideInk()](#getHideInk--) | Megjeleníti vagy elrejti az Ink elemeket az exportált dokumentumban. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Megjeleníti vagy elrejti az Ink elemeket az exportált dokumentumban. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | ROP műveletet vagy átlátszóságot használ az ecset rendereléséhez. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | ROP műveletet vagy átlátszóságot használ az ecset rendereléséhez. |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
```


Megjeleníti vagy elrejti az Ink elemeket az exportált dokumentumban.

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

Az alapértelmezett érték hamis.

**Visszatérési érték:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
```


Megjeleníti vagy elrejti az Ink elemeket az exportált dokumentumban.

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

Az alapértelmezett érték hamis.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```


ROP műveletet vagy átlátszóságot használ az ecset rendereléséhez.

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

Az alapértelmezett érték igaz.

**Visszatérési érték:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```


ROP műveletet vagy átlátszóságot használ az ecset rendereléséhez.

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

Az alapértelmezett érték igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |