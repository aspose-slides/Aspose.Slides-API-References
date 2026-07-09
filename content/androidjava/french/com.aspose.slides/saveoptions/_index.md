---
title: SaveOptions
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Classe abstraite avec des options qui contrôlent la façon dont une présentation est enregistrée.
type: docs
url: /fr/com.aspose.slides/saveoptions/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

Classe abstraite avec des options qui contrôlent la façon dont une présentation est enregistrée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être abandonné. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être abandonné. |
| [getProgressCallback()](#getProgressCallback--) | Représente un objet de rappel pour les mises à jour de progression de l’enregistrement en pourcentage. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Représente un objet de rappel pour les mises à jour de progression de l’enregistrement en pourcentage. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Renvoie ou définit la police utilisée si la police source n’est pas trouvée. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Renvoie ou définit la police utilisée si la police source n’est pas trouvée. |
| [getGradientStyle()](#getGradientStyle--) | Renvoie ou définit le style visuel du dégradé. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Renvoie ou définit le style visuel du dégradé. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Spécifie si les hyperliens contenant des appels JavaScript doivent être ignorés lors de l’enregistrement de la présentation. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Spécifie si les hyperliens contenant des appels JavaScript doivent être ignorés lors de l’enregistrement de la présentation. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être abandonné. Lecture/écriture [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Renvoie :**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être abandonné. Lecture/écriture [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```


Représente un objet de rappel pour les mises à jour de progression de l’enregistrement en pourcentage. Voir [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Renvoie :**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```


Représente un objet de rappel pour les mises à jour de progression de l’enregistrement en pourcentage. Voir [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


Renvoie ou définit la police utilisée si la police source n’est pas trouvée. Lecture/écriture String.

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
public final void setDefaultRegularFont(String value)
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
public final int getGradientStyle()
```

Returns or sets the visual style of the gradient. Read/write [GradientStyle](../../com.aspose.slides/gradientstyle).

**Returns:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```


Returns or sets the visual style of the gradient. Read/write [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
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
public final void setSkipJavaScriptLinks(boolean value)

Spécifie si les hyperliens contenant des appels JavaScript doivent être ignorés lors de l’enregistrement de la présentation. Lecture/écriture booléen. La valeur par défaut est false.

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

Lorsque cette propriété est définie sur true, les hyperliens contenant des appels JavaScript seront ignorés lors de l’enregistrement.

Lorsque cette propriété est définie sur false, tous les hyperliens seront enregistrés.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |