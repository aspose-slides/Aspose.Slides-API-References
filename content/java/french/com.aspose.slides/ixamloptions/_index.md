---
title: IXamlOptions
second_title: Référence de l'API Aspose.Slides pour Java
description: Options qui contrôlent la façon dont un document XAML est enregistré.
type: docs
url: /fr/com.aspose.slides/ixamloptions/
---
**Toutes les interfaces implémentées:**  
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
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
## Méthodes

| Méthode | Description |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Détermine si les diapositives cachées seront exportées. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Détermine si les diapositives cachées seront exportées. |
| [getOutputSaver()](#getOutputSaver--) | Représente une implémentation de l'interface IOutputSaver. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Représente une implémentation de l'interface IOutputSaver. |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


Détermine si les diapositives cachées seront exportées.

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
public abstract void setExportHiddenSlides(boolean value)
```


Détermine si les diapositives cachées seront exportées.

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
public abstract IXamlOutputSaver getOutputSaver()
```


Représente une implémentation de l'interface IOutputSaver.

**Retour :**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```


Représente une implémentation de l'interface IOutputSaver.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |