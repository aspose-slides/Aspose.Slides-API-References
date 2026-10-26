---
title: IInkOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Opciókat biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban.
type: docs
url: /hu/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

Opciókat biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getHideInk()](#getHideInk--) | Megjeleníti vagy elrejti az Ink elemeket az exportált dokumentumban. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Megjeleníti vagy elrejti az Ink elemeket az exportált dokumentumban. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | ROP műveletet vagy átlátszóságot használ az ecset rendereléséhez. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | ROP műveletet vagy átlátszóságot használ az ecset rendereléséhez. |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
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
public abstract void setHideInk(boolean value)
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
public abstract boolean getInterpretMaskOpAsOpacity()
```

ROP műveletet vagy átlátszóságot használ az ecset rendereléséhez.

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

Az alapértelmezett érték igaz.

**Visszatérési érték:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```

ROP műveletet vagy átlátszóságot használ az ecset rendereléséhez.

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

Az alapértelmezett érték igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |