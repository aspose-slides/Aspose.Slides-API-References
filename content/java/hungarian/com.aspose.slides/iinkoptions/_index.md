---
title: IInkOptions
second_title: Aspose.Slides for Java API Reference
description: Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban.
type: docs
url: /hu/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban.
## Metódusok

| Method | Description |
| --- | --- |
| [getHideInk()](#getHideInk--) | Megjeleníti vagy elrejti az Ink elemeket az exportált dokumentumban. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Megjeleníti vagy elrejti az Ink elemeket az exportált dokumentumban. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | ROP műveletet vagy Opacity-t használ a ecset rendereléséhez. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | ROP műveletet vagy Opacity-t használ a ecset rendereléséhez. |
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

Az alapértelmezett érték false.

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

Az alapértelmezett érték false.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public abstract boolean getInterpretMaskOpAsOpacity()
```


ROP műveletet vagy Opacity-t használ a ecset rendereléséhez.

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

Az alapértelmezett érték true.

**Visszatérési érték:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```


ROP műveletet vagy Opacity-t használ a ecset rendereléséhez.

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

Az alapértelmezett érték true.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |