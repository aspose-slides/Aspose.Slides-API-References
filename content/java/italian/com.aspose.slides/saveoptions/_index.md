---
title: SaveOptions
second_title: Riferimento API di Aspose.Slides per Java
description: Classe astratta con opzioni che controllano come una presentazione viene salvata.
type: docs
url: /it/com.aspose.slides/saveoptions/
---
**Eredità:**
java.lang.Object

**Tutte le Interfacce Implementate:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

Classe astratta con opzioni che controllano come una presentazione viene salvata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto. |
| [getProgressCallback()](#getProgressCallback--) | Rappresenta un oggetto di callback per gli aggiornamenti di avanzamento del salvataggio in percentuale. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Rappresenta un oggetto di callback per gli aggiornamenti di avanzamento del salvataggio in percentuale. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Restituisce o imposta il font utilizzato nel caso in cui il font di origine non venga trovato. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Restituisce o imposta il font utilizzato nel caso in cui il font di origine non venga trovato. |
| [getGradientStyle()](#getGradientStyle--) | Restituisce o imposta lo stile visuale del gradiente. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Restituisce o imposta lo stile visuale del gradiente. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto. Lettura/scrittura [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Restituisce:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto. Lettura/scrittura [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```


Rappresenta un oggetto di callback per gli aggiornamenti di avanzamento del salvataggio in percentuale. Vedi [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Restituisce:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```


Rappresenta un oggetto di callback per gli aggiornamenti di avanzamento del salvataggio in percentuale. Vedi [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


Restituisce o imposta il font utilizzato nel caso in cui il font di origine non venga trovato. Lettura-scrittura String.

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


**Restituisce:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```


Restituisce o imposta il font utilizzato nel caso in cui il font di origine non venga trovato. Lettura-scrittura String.

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


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public final int getGradientStyle()
```


Restituisce o imposta lo stile visuale del gradiente. Lettura/scrittura [GradientStyle](../../com.aspose.slides/gradientstyle).

**Restituisce:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```


Restituisce o imposta lo stile visuale del gradiente. Lettura/scrittura [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```


Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Lettura/scrittura boolean. Il valore predefinito è false.

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

Quando questa proprietà è impostata su true, i collegamenti ipertestuali con chiamate JavaScript saranno ignorati durante il salvataggio.

Quando questa proprietà è impostata su false, tutti i collegamenti ipertestuali saranno salvati.

**Restituisce:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```


Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Lettura/scrittura boolean. Il valore predefinito è false.

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

Quando questa proprietà è impostata su true, i collegamenti ipertestuali con chiamate JavaScript saranno ignorati durante il salvataggio.

Quando questa proprietà è impostata su false, tutti i collegamenti ipertestuali saranno salvati.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |