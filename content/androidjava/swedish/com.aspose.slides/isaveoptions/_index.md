---
title: ISaveOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Options that control how a presentation is saved.
type: docs
url: /sv/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

Alternativ som styr hur en presentation sparas.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Returnerar eller anger ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Returnerar eller anger ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas. |
| [getProgressCallback()](#getProgressCallback--) | Representerar ett återuppringningsobjekt för sparningsförloppsuppdateringar i procent. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Representerar ett återuppringningsobjekt för sparningsförloppsuppdateringar i procent. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Returnerar eller anger ett teckensnitt som används om källteckensnittet inte finns. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Returnerar eller anger ett teckensnitt som används om källteckensnittet inte finns. |
| [getGradientStyle()](#getGradientStyle--) | Returnerar eller anger den visuella stilen för gradienten. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Returnerar eller anger den visuella stilen för gradienten. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Anger om hyperlänkar med JavaScript-anrop ska hoppas över vid sparning av presentationen. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Anger om hyperlänkar med JavaScript-anrop ska hoppas över vid sparning av presentationen. |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```


Returnerar eller anger ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas. Läs/skriv [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Returnerar:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```


Returnerar eller anger ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas. Läs/skriv [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```


Representerar ett återuppringningsobjekt för sparningsförloppsuppdateringar i procent. Se [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Returnerar:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```


Representerar ett återuppringningsobjekt för sparningsförloppsuppdateringar i procent. Se [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```


Returnerar eller anger ett teckensnitt som används om källteckensnittet inte finns. Läs-skriv String.

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


**Returnerar:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```


Returnerar eller anger ett teckensnitt som används om källteckensnittet inte finns. Läs-skriv String.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public abstract int getGradientStyle()
```


Returnerar eller anger den visuella stilen för gradienten. Läs/skriv [GradientStyle](../../com.aspose.slides/gradientstyle).

**Returnerar:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```


Returnerar eller anger den visuella stilen för gradienten. Läs/skriv [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```


Anger om hyperlänkar med JavaScript-anrop ska hoppas över vid sparning av presentationen. Läs/skriv boolean. Standardvärdet är falskt.

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

När den här egenskapen är satt till true ignoreras hyperlänkar med JavaScript-anrop vid sparning.

När den här egenskapen är satt till false sparas alla hyperlänkar.

**Returnerar:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```


Anger om hyperlänkar med JavaScript-anrop ska hoppas över vid sparning av presentationen. Läs/skriv boolean. Standardvärdet är falskt.

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

När den här egenskapen är satt till true ignoreras hyperlänkar med JavaScript-anrop vid sparning.

När den här egenskapen är satt till false sparas alla hyperlänkar.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |