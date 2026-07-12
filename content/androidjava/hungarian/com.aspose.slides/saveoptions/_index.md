---
title: SaveOptions
second_title: Aspose.Slides Androidra Java API hivatkozás
description: Absztrakt osztály olyan beállításokkal, amelyek szabályozzák, hogyan mentődik a bemutató.
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

Absztrakt osztály olyan beállításokkal, amelyek szabályozzák, hogyan mentődik a bemutató.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és meghatározza, hogy a betöltési folyamat folytatódik-e vagy megszakad. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és meghatározza, hogy a betöltési folyamat folytatódik-e vagy megszakad. |
| [getProgressCallback()](#getProgressCallback--) | Egy visszahívási objektum, amely a mentés előrehaladását százalékban jelzi. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Egy visszahívási objektum, amely a mentés előrehaladását százalékban jelzi. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Visszaadja vagy beállítja azt a betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Visszaadja vagy beállítja azt a betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található. |
| [getGradientStyle()](#getGradientStyle--) | Visszaadja vagy beállítja a gradient vizuális stílusát. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Visszaadja vagy beállítja a gradient vizuális stílusát. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Megadja, hogy a bemutató mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Megadja, hogy a bemutató mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és meghatározza, hogy a betöltési folyamat folytatódik-e vagy megszakad. Olvasás/írás [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Visszatérési érték:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és meghatározza, hogy a betöltési folyamat folytatódik-e vagy megszakad. Olvasás/írás [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```


Egy visszahívási objektum, amely a mentés előrehaladását százalékban jelzi. Lásd [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Visszatérési érték:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```


Egy visszahívási objektum, amely a mentés előrehaladását százalékban jelzi. Lásd [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


Visszaadja vagy beállítja azt a betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található. Olvasás/írás String.

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


Visszaadja vagy beállítja azt a betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található. Olvasás/írás String.

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


Visszaadja vagy beállítja a gradient vizuális stílusát. Olvasás/írás [GradientStyle](../../com.aspose.slides/gradientstyle).

**Visszatérési érték:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```


Visszaadja vagy beállítja a gradient vizuális stílusát. Olvasás/írás [GradientStyle](../../com.aspose.slides/gradientstyle).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```


Megadja, hogy a bemutató mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Olvasás/írás boolean. Az alapértelmezett érték hamis.

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

Ha ez a tulajdonság igazra van állítva, a JavaScript hívásokat tartalmazó hiperhivatkozások mentés közben figyelmen kívül lesznek hagyva.

Ha ez a tulajdonság hamisra van állítva, az összes hiperhivatkozás mentésre kerül.

**Visszatérési érték:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```


Megadja, hogy a bemutató mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Olvasás/írás boolean. Az alapértelmezett érték hamis.

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

Ha ez a tulajdonság igazra van állítva, a JavaScript hívásokat tartalmazó hiperhivatkozások mentés közben figyelmen kívül lesznek hagyva.

Ha ez a tulajdonság hamisra van állítva, az összes hiperhivatkozás mentésre kerül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |