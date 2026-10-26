---
title: ISaveOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Opties die bepalen hoe een presentatie wordt opgeslagen.
type: docs
url: /nl/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

Opties die bepalen hoe een presentatie wordt opgeslagen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Geeft een object terug of stelt het in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Geeft een object terug of stelt het in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. |
| [getProgressCallback()](#getProgressCallback--) | Stelt een callback-object voor voor voortgangsupdates bij het opslaan in procenten. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Stelt een callback-object voor voor voortgangsupdates bij het opslaan in procenten. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Geeft het lettertype terug of stelt het in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Geeft het lettertype terug of stelt het in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. |
| [getGradientStyle()](#getGradientStyle--) | Geeft de visuele stijl van de verloop terug of stelt deze in. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Geeft de visuele stijl van de verloop terug of stelt deze in. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Specificeert of hyperlinks met JavaScript-oproepen worden overgeslagen bij het opslaan van de presentatie. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Specificeert of hyperlinks met JavaScript-oproepen worden overgeslagen bij het opslaan van de presentatie. |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Geeft een object terug of stelt het in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lezen/Schrijven [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Retour:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Geeft een object terug of stelt het in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lezen/Schrijven [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```

Stelt een callback-object voor voor voortgangsupdates bij het opslaan in procenten. Zie [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Retour:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```

Stelt een callback-object voor voor voortgangsupdates bij het opslaan in procenten. Zie [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Geeft het lettertype terug of stelt het in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Lezen-Schrijven String.

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
public abstract void setDefaultRegularFont(String value)
```

Geeft het lettertype terug of stelt het in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Lezen-Schrijven String.

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
public abstract int getGradientStyle()
```

Geeft de visuele stijl van de verloop terug of stelt deze in. Lezen/Schrijven [GradientStyle](../../com.aspose.slides/gradientstyle).

**Retour:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```

Geeft de visuele stijl van de verloop terug of stelt deze in. Lezen/Schrijven [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```

Specificeert of hyperlinks met JavaScript-oproepen worden overgeslagen bij het opslaan van de presentatie. Lezen/Schrijven boolean. De standaardwaarde is false.

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

Wanneer deze eigenschap op true wordt gezet, zullen hyperlinks met JavaScript-oproepen worden genegeerd tijdens het opslaan.

Wanneer deze eigenschap op false wordt gezet, worden alle hyperlinks opgeslagen.

**Retour:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```

Specificeert of hyperlinks met JavaScript-oproepen worden overgeslagen bij het opslaan van de presentatie. Lezen/Schrijven boolean. De standaardwaarde is false.

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

Wanneer deze eigenschap op true wordt gezet, zullen hyperlinks met JavaScript-oproepen worden genegeerd tijdens het opslaan.

Wanneer deze eigenschap op false wordt gezet, worden alle hyperlinks opgeslagen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |