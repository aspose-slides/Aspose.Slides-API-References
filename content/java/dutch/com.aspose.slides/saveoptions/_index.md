---
title: SaveOptions
second_title: Aspose.Slides voor Java API-referentie
description: Abstracte klasse met opties die bepalen hoe een presentatie wordt opgeslagen.
type: docs
url: /nl/com.aspose.slides/saveoptions/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

Abstracte klasse met opties die bepalen hoe een presentatie wordt opgeslagen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## Methods

| Methode | Beschrijving |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. |
| [getProgressCallback()](#getProgressCallback--) | Stelt een callback-object voor voor opslaan voortgangsupdates in procenten. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Stelt een callback-object voor voor opslaan voortgangsupdates in procenten. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Retourneert of stelt het lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Retourneert of stelt het lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. |
| [getGradientStyle()](#getGradientStyle--) | Retourneert of stelt de visuele stijl van de gradient in. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Retourneert of stelt de visuele stijl van de gradient in. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Specificeert of hyperlinks met JavaScript-aanroepen overgeslagen moeten worden bij het opslaan van de presentatie. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Specificeert of hyperlinks met JavaScript-aanroepen overgeslagen moeten worden bij het opslaan van de presentatie. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lezen/schrijven [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Retourneert:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lezen/schrijven [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```


Stelt een callback-object voor voor opslaan voortgangsupdates in procenten. Zie [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Retourneert:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```


Stelt een callback-object voor voor opslaan voortgangsupdates in procenten. Zie [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


Retourneert of stelt het lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. Lezen/schrijven String.

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


**Retourneert:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```


Retourneert of stelt het lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. Lezen/schrijven String.

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


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public final int getGradientStyle()
```


Retourneert of stelt de visuele stijl van de gradient in. Lezen/schrijven [GradientStyle](../../com.aspose.slides/gradientstyle).

**Retourneert:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```


Retourneert of stelt de visuele stijl van de gradient in. Lezen/schrijven [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```


Specificeert of hyperlinks met JavaScript-aanroepen overgeslagen moeten worden bij het opslaan van de presentatie. Lezen/schrijven boolean. De standaardwaarde is false.

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

Wanneer deze eigenschap op true wordt gezet, worden hyperlinks met JavaScript-aanroepen genegeerd tijdens het opslaan.

Wanneer deze eigenschap op false wordt gezet, worden alle hyperlinks opgeslagen.

**Retourneert:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```


Specificeert of hyperlinks met JavaScript-aanroepen overgeslagen moeten worden bij het opslaan van de presentatie. Lezen/schrijven boolean. De standaardwaarde is false.

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

Wanneer deze eigenschap op true wordt gezet, worden hyperlinks met JavaScript-aanroepen genegeerd tijdens het opslaan.

Wanneer deze eigenschap op false wordt gezet, worden alle hyperlinks opgeslagen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
