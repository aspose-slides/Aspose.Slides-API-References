---
title: SaveOptions
second_title: Référence de l'API Aspose.Slides pour Java
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
| [getWarningCallback()](#getWarningCallback--) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement continue ou est interrompu. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement continue ou est interrompu. |
| [getProgressCallback()](#getProgressCallback--) | Représente un objet de rappel pour les mises à jour de progression de sauvegarde en pourcentage. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Représente un objet de rappel pour les mises à jour de progression de sauvegarde en pourcentage. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Renvoie ou définit la police utilisée si la police source n’est pas trouvée. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Renvoie ou définit la police utilisée si la police source n’est pas trouvée. |
| [getGradientStyle()](#getGradientStyle--) | Renvoie ou définit le style visuel du dégradé. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Renvoie ou définit le style visuel du dégradé. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Spécifie s’il faut ignorer les hyperliens avec des appels JavaScript lors de la sauvegarde de la présentation. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Spécifie s’il faut ignorer les hyperliens avec des appels JavaScript lors de la sauvegarde de la présentation. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement continue ou est interrompu. Lecture/écriture [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Renvoie :**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement continue ou est interrompu. Lecture/écriture [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```

Représente un objet de rappel pour les mises à jour de progression de sauvegarde en pourcentage. Voir [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Renvoie :**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```

Représente un objet de rappel pour les mises à jour de progression de sauvegarde en pourcentage. Voir [IProgressCallback](../../com.aspose.slides/iprogresscallback).

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


**Renvoie :**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public final int getGradientStyle()
```

Renvoie ou définit le style visuel du dégradé. Lecture/écriture [GradientStyle](../../com.aspose.slides/gradientstyle).

**Renvoie :**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```

Renvoie ou définit le style visuel du dégradé. Lecture/écriture [GradientStyle](../../com.aspose.slides/gradientstyle).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```

Spécifie s’il faut ignorer les hyperliens avec des appels JavaScript lors de la sauvegarde de la présentation. Lecture/écriture booléen. La valeur par défaut est false.

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


Lorsque cette propriété est définie sur true, les hyperliens avec des appels JavaScript seront ignorés lors de la sauvegarde.

Lorsque cette propriété est définie sur false, tous les hyperliens seront sauvegardés.

**Renvoie :**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```

Spécifie s’il faut ignorer les hyperliens avec des appels JavaScript lors de la sauvegarde de la présentation. Lecture/écriture booléen. La valeur par défaut est false.

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

Lorsque cette propriété est définie sur true, les hyperliens avec des appels JavaScript seront ignorés lors de la sauvegarde.

Lorsque cette propriété est définie sur false, tous les hyperliens seront sauvegardés.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |