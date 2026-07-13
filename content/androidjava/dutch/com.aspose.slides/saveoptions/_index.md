---
title: SaveOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Abstracte klasse met opties die bepalen hoe een presentatie wordt opgeslagen.
type: docs
url: /nl/com.aspose.slides/saveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
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
| [getWarningCallback()](#getWarningCallback--) | Geeft een object terug of stelt een object in dat waarschuwingen ontvangt en bepaalt of het laadproces wordt voortgezet of wordt afgebroken. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Geeft een object terug of stelt een object in dat waarschuwingen ontvangt en bepaalt of het laadproces wordt voortgezet of wordt afgebroken. |
| [getProgressCallback()](#getProgressCallback--) | Stelt een callback-object voor dat voortgangsupdates bij het opslaan weergeeft in percentage. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Stelt een callback-object voor dat voortgangsupdates bij het opslaan weergeeft in percentage. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Geeft een lettertype terug of stelt een lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Geeft een lettertype terug of stelt een lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. |
| [getGradientStyle()](#getGradientStyle--) | Geeft de visuele stijl van de gradient terug of stelt deze in. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Geeft de visuele stijl van de gradient terug of stelt deze in. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Geeft aan of hyperlinks met JavaScript-aanroepen moeten worden overgeslagen bij het opslaan van de presentatie. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Geeft aan of hyperlinks met JavaScript-aanroepen moeten worden overgeslagen bij het opslaan van de presentatie. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Geeft een object terug of stelt een object in dat waarschuwingen ontvangt en bepaalt of het laadproces wordt voortgezet of wordt afgebroken. Lezen/schrijven [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Retour:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Geeft een object terug of stelt een object in dat waarschuwingen ontvangt en bepaalt of het laadproces wordt voortgezet of wordt afgebroken. Lezen/schrijven [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```

Stelt een callback-object voor dat voortgangsupdates bij het opslaan weergeeft in percentage. Zie [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Retour:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```

Stelt een callback-object voor dat voortgangsupdates bij het opslaan weergeeft in percentage. Zie [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Geeft een lettertype terug of stelt een lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Lezen-schrijven String.

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


**Retour:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Geeft een lettertype terug of stelt een lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Lezen-schrijven String.

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

Geeft de visuele stijl van de gradient terug of stelt deze in. Lezen/schrijven [GradientStyle](../../com.aspose.slides/gradientstyle).

**Retour:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```

Geeft de visuele stijl van de gradient terug of stelt deze in. Lezen/schrijven [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```

Geeft aan of hyperlinks met JavaScript-aanroepen moeten worden overgeslagen bij het opslaan van de presentatie. Lezen/schrijven boolean. De standaardwaarde is false.

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

Wanneer deze eigenschap is ingesteld op true, worden hyperlinks met JavaScript-aanroepen genegeerd tijdens het opslaan.

Wanneer deze eigenschap is ingesteld op false, worden alle hyperlinks opgeslagen.

**Retour:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```

Geeft aan of hyperlinks met JavaScript-aanroepen moeten worden overgeslagen bij het opslaan van de presentatie. Lezen/schrijven boolean. De standaardwaarde is false.

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

Wanneer deze eigenschap is ingesteld op true, worden hyperlinks met JavaScript-aanroepen genegeerd tijdens het opslaan.

Wanneer deze eigenschap is ingesteld op false, worden alle hyperlinks opgeslagen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |