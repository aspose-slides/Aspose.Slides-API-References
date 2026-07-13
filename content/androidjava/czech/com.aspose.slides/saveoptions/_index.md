---
title: SaveOptions
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Abstraktní třída s možnostmi, které řídí, jak je prezentace uložena.
type: docs
url: /cs/com.aspose.slides/saveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

Abstraktní třída s možnostmi, které řídí, jak je prezentace uložena.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. |
| [getProgressCallback()](#getProgressCallback--) | Reprezentuje zpětný volací objekt pro aktualizace postupu ukládání v procentech. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Reprezentuje zpětný volací objekt pro aktualizace postupu ukládání v procentech. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Vrací nebo nastavuje písmo použité v případě, že zdrojové písmo není nalezeno. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Vrací nebo nastavuje písmo použité v případě, že zdrojové písmo není nalezeno. |
| [getGradientStyle()](#getGradientStyle--) | Vrací nebo nastavuje vizuální styl gradientu. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Vrací nebo nastavuje vizuální styl gradientu. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. Číst/zapisovat [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Vrací:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. Číst/zapisovat [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```


Reprezentuje zpětný volací objekt pro aktualizace postupu ukládání v procentech. Viz [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Vrací:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```


Reprezentuje zpětný volací objekt pro aktualizace postupu ukládání v procentech. Viz [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


Vrací nebo nastavuje písmo použité v případě, že zdrojové písmo není nalezeno. Číst/zapisovat String.

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

**Vrací:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```


Vrací nebo nastavuje písmo použité v případě, že zdrojové písmo není nalezeno. Číst/zapisovat String.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public final int getGradientStyle()
```


Vrací nebo nastavuje vizuální styl gradientu. Číst/zapisovat [GradientStyle](../../com.aspose.slides/gradientstyle).

**Vrací:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```


Vrací nebo nastavuje vizuální styl gradientu. Číst/zapisovat [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```


Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. Číst/zapisovat boolean. Výchozí hodnota je false.

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

Když je tato vlastnost nastavena na true, budou při ukládání ignorovány hypertextové odkazy s voláním JavaScriptu.

Když je tato vlastnost nastavena na false, všechny hypertextové odkazy budou uloženy.

**Vrací:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```


Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. Číst/zapisovat boolean. Výchozí hodnota je false.

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

Když je tato vlastnost nastavena na true, budou při ukládání ignorovány hypertextové odkazy s voláním JavaScriptu.

Když je tato vlastnost nastavena na false, všechny hypertextové odkazy budou uloženy.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |