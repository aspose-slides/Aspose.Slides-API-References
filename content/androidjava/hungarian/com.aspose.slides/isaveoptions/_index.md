---
title: ISaveOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Az opciók, amelyek szabályozzák, hogyan mentődik a prezentáció.
type: docs
url: /hu/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

Az opciók, amelyek szabályozzák, hogyan mentődik a prezentáció.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. |
| [getProgressCallback()](#getProgressCallback--) | Egy visszahívási objektumot képvisel, amely a mentés előrehaladását százalékban jelzi. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Egy visszahívási objektumot képvisel, amely a mentés előrehaladását százalékban jelzi. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Visszaad vagy beállít egy betűtípust, amely akkor használatos, ha a forrásbetűtípus nem található. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Visszaad vagy beállít egy betűtípust, amely akkor használatos, ha a forrásbetűtípus nem található. |
| [getGradientStyle()](#getGradientStyle--) | Visszaad vagy beállítja a gradiens vizuális stílusát. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Visszaad vagy beállítja a gradiens vizuális stílusát. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Megadja, hogy a bemutató mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Megadja, hogy a bemutató mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. Olvasás/írás [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Visszatér:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. Olvasás/írás [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```

Egy visszahívási objektumot képvisel, amely a mentés előrehaladását százalékban jelzi. Lásd [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Visszatér:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```

Egy visszahívási objektumot képvisel, amely a mentés előrehaladását százalékban jelzi. Lásd [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Visszaad vagy beállít egy betűtípust, amely akkor használatos, ha a forrásbetűtípus nem található. Olvasás/írás String.

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


**Visszatér:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Visszaad vagy beállít egy betűtípust, amely akkor használatos, ha a forrásbetűtípus nem található. Olvasás/írás String.

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
public abstract int getGradientStyle()
```

Visszaad vagy beállítja a gradiens vizuális stílusát. Olvasás/írás [GradientStyle](../../com.aspose.slides/gradientstyle).

**Visszatér:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```

Visszaad vagy beállítja a gradiens vizuális stílusát. Olvasás/írás [GradientStyle](../../com.aspose.slides/gradientstyle).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
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

Ha ez a tulajdonság igazra van állítva, a JavaScript hívásokat tartalmazó hiperhivatkozások mentés közben figyelmen kívül maradnak.

Ha ez a tulajdonság hamisra van állítva, az összes hiperhivatkozás mentésre kerül.

**Visszatér:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
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

Ha ez a tulajdonság igazra van állítva, a JavaScript hívásokat tartalmazó hiperhivatkozások mentés közben figyelmen kívül maradnak.

Ha ez a tulajdonság hamisra van állítva, az összes hiperhivatkozás mentésre kerül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |