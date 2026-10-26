---
title: SaveOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Abstrakt klass med alternativ som styr hur en presentation sparas.
type: docs
url: /sv/com.aspose.slides/saveoptions/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

Abstrakt klass med alternativ som styr hur en presentation sparas.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Returnerar eller sätter ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Returnerar eller sätter ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas. |
| [getProgressCallback()](#getProgressCallback--) | Representerar ett återuppringningsobjekt för sparande av framstegsupdateringar i procent. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Representerar ett återuppringningsobjekt för sparande av framstegsupdateringar i procent. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Returnerar eller sätter teckensnitt som används om källteckensnittet inte hittas. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Returnerar eller sätter teckensnitt som används om källteckensnittet inte hittas. |
| [getGradientStyle()](#getGradientStyle--) | Returnerar eller sätter den visuella stilen för gradienten. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Returnerar eller sätter den visuella stilen för gradienten. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


Returnerar eller sätter ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas. Läs/skriv [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Returnerar:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


Returnerar eller sätter ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas. Läs/skriv [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```


Representerar ett återuppringningsobjekt för sparande av framstegsupdateringar i procent. Se [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Returnerar:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```


Representerar ett återuppringningsobjekt för sparande av framstegsupdateringar i procent. Se [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


Returnerar eller sätter teckensnitt som används om källteckensnittet inte hittas. Läs/skriv String.

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
public final void setDefaultRegularFont(String value)
```


Returnerar eller sätter teckensnitt som används om källteckensnittet inte hittas. Läs/skriv String.

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
public final int getGradientStyle()
```


Returnerar eller sätter den visuella stilen för gradienten. Läs/skriv [GradientStyle](../../com.aspose.slides/gradientstyle).

**Returnerar:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```


Returnerar eller sätter den visuella stilen för gradienten. Läs/skriv [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```


Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. Läs/skriv boolean. Standardvärdet är false.

**Returnerar:**
boolean
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

När denna egenskap är satt till true kommer hyperlänkar med JavaScript-anrop att ignoreras vid sparning.

När denna egenskap är satt till false kommer alla hyperlänkar att sparas.

**Returnerar:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```


Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. Läs/skriv boolean. Standardvärdet är false.

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

När denna egenskap är satt till true kommer hyperlänkar med JavaScript-anrop att ignoreras vid sparning.

När denna egenskap är satt till false kommer alla hyperlänkar att sparas.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |