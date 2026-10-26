---
title: SaveOptions
second_title: Aspose.Slides for Java API Referenciája
description: Absztrakt osztály, amely beállításokkal rendelkezik, és szabályozza, hogyan menthető egy prezentáció.
type: docs
url: /hu/com.aspose.slides/saveoptions/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

Absztrakt osztály opciókkal, amelyek szabályozzák, hogyan mentődik a prezentáció.
## Constructors

| Konstruktor | Leírás |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## Methods

| Metódus | Leírás |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap, és dönt arról, hogy a betöltési folyamat folytatódik-e vagy megszakad. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap, és dönt arról, hogy a betöltési folyamat folytatódik-e vagy megszakad. |
| [getProgressCallback()](#getProgressCallback--) | Egy visszahívási objektumot képvisel, amely a mentés előrehaladását százalékban jelzi. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Egy visszahívási objektumot képvisel, amely a mentés előrehaladását százalékban jelzi. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Visszaad vagy beállít egy betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Visszaad vagy beállít egy betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található. |
| [getGradientStyle()](#getGradientStyle--) | Visszaad vagy beállítja a gradient vizuális stílusát. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Visszaad vagy beállítja a gradient vizuális stílusát. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Megadja, hogy a prezentáció mentése során kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Megadja, hogy a prezentáció mentése során kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap, és dönt arról, hogy a betöltési folyamat folytatódik-e vagy megszakad. Olvasás/írás [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Visszatérési érték:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap, és dönt arról, hogy a betöltési folyamat folytatódik-e vagy megszakad. Olvasás/írás [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```


Egy visszahívási objektumot képvisel, amely a mentés előrehaladását százalékban jelzi. Lásd [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Visszatérési érték:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```


Egy visszahívási objektumot képvisel, amely a mentés előrehaladását százalékban jelzi. Lásd [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


Visszaad vagy beállít egy betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található. Olvasás-írás String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```


Visszaad vagy beállít egy betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található. Olvasás-írás String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public final int getGradientStyle()
```


Visszaad vagy beállítja a gradient vizuális stílusát. Olvasás/írás [GradientStyle](../../com.aspose.slides/gradientstyle).

**Visszatérési érték:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```


Visszaad vagy beállítja a gradient vizuális stílusát. Olvasás/írás [GradientStyle](../../com.aspose.slides/gradientstyle).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```


Megadja, hogy a prezentáció mentése során kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Olvasás/írás boolean. Az alapértelmezett érték hamis.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Amikor ezt a tulajdonságot true-ra állítják, a JavaScript hívásokat tartalmazó hiperhivatkozások figyelmen kívül maradnak a mentés során.

Amikor ezt a tulajdonságot false-ra állítják, az összes hiperhivatkozás el lesz mentve.

**Visszatérési érték:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```


Megadja, hogy a prezentáció mentése során kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Olvasás/írás boolean. Az alapértelmezett érték hamis.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Amikor ezt a tulajdonságot true-ra állítják, a JavaScript hívásokat tartalmazó hiperhivatkozások figyelmen kívül maradnak a mentés során.

Amikor ezt a tulajdonságot false-ra állítják, az összes hiperhivatkozás el lesz mentve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |