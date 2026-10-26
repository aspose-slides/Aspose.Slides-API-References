---
title: XamlOptions
second_title: Référence de l'API Aspose.Slides pour Java
description: Options qui contrôlent la façon dont un document XAML est enregistré.
type: docs
url: /fr/com.aspose.slides/xamloptions/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
```

Options qui contrôlent la façon dont un document XAML est enregistré.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | Crée l'instance XamlOptions. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Détermine si les diapositives masquées seront exportées. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Détermine si les diapositives masquées seront exportées. |
| [getOutputSaver()](#getOutputSaver--) | Représente une implémentation de l'interface IOutputSaver. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Représente une implémentation de l'interface IOutputSaver. |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```


Crée l'instance XamlOptions.

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


Détermine si les diapositives masquées seront exportées.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retour :**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```


Détermine si les diapositives masquées seront exportées.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public final IXamlOutputSaver getOutputSaver()
```


Représente une implémentation de l'interface IOutputSaver.

**Retour :**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```


Représente une implémentation de l'interface IOutputSaver.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |