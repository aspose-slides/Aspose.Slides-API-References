---
title: InkOptions
second_title: Aspose.Slides Androidhoz a Java API hivatkozással
description: Beállításokat biztosít, amelyek az Ink objektumok megjelenését szabályozzák az exportált dokumentumban.
type: docs
url: /hu/com.aspose.slides/inkoptions/
---
**Öröklés:**  
java.lang.Object

**Minden implementált interfész:**  
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)  
```
public class InkOptions implements IInkOptions
```

Beállításokat biztosít, amelyek az Ink objektumok megjelenését szabályozzák az exportált dokumentumban.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getHideInk()](#getHideInk--) | Megjeleníti vagy elrejti az Ink elemeket az exportált dokumentumban. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Megjeleníti vagy elrejti az Ink elemeket az exportált dokumentumban. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | ROP műveletet vagy Opacity-t használ a ecset megjelenítéséhez. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | ROP műveletet vagy Opacity-t használ a ecset megjelenítéséhez. |

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

Alapértelmezett érték false.

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

Alapértelmezett érték false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```

ROP műveletet vagy Opacity-t használ a ecset megjelenítéséhez.

--------------------

> ```
> A következő példa bemutatja, hogyan állítható be a ROP használata az Ink elemek exportálásához:
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

Alapértelmezett érték true.

**Visszatérési érték:**  
boolean

### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```

ROP műveletet vagy Opacity-t használ a ecset megjelenítéséhez.

--------------------

> ```
> A következő példa bemutatja, hogyan állítható be a ROP használata az Ink elemek exportálásához:
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

Alapértelmezett érték true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |