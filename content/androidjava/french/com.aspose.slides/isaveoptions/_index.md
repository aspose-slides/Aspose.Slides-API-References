---
title: ISaveOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Options qui contrôlent la manière dont une présentation est enregistrée.
type: docs
url: /fr/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

Options qui contrôlent la manière dont une présentation est enregistrée.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. |
| [getProgressCallback()](#getProgressCallback--) | Represents a callback object for saving progress updates in percentage. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Represents a callback object for saving progress updates in percentage. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Returns or sets font used in case source font is not found. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Returns or sets font used in case source font is not found. |
| [getGradientStyle()](#getGradientStyle--) | Returns or sets the visual style of the gradient. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Returns or sets the visual style of the gradient. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit continuer ou être interrompu. Lecture/écriture [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Retour:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit continuer ou être interrompu. Lecture/écriture [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |
### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```

Représente un objet de rappel pour les mises à jour de progression de l'enregistrement en pourcentage. Voir [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Retour:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```

Représente un objet de rappel pour les mises à jour de progression de l'enregistrement en pourcentage. Voir [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |
### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Renvoie ou définit la police utilisée si la police source n'est pas trouvée. Lecture/écriture String.

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

**Returns:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Returns or sets font used in case source font is not found. Read-write String.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public abstract int getGradientStyle()
```

Returns or sets the visual style of the gradient. Read/write [GradientStyle](../../com.aspose.slides/gradientstyle).

**Returns:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```

Returns or sets the visual style of the gradient. Read/write [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```

Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. Read/write boolean. The default value is false.

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

When this property is set to true, hyperlinks with JavaScript calls will be ignored while saving.

When this property is set to false, all hyperlinks will be saved.

**Returns:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)


Spécifie si les hyperliens contenant des appels JavaScript doivent être ignorés lors de l'enregistrement de la présentation. Lecture/écriture boolean. La valeur par défaut est false.

--------------------

> ```
> Exemple :
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

Lorsque cette propriété est définie sur true, les hyperliens contenant des appels JavaScript seront ignorés lors de l'enregistrement.

Lorsque cette propriété est définie sur false, tous les hyperliens seront enregistrés.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
