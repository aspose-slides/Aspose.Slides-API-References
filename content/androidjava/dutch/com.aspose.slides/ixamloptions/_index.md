---
title: IXamlOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Opties die bepalen hoe een XAML-document wordt opgeslagen.
type: docs
url: /nl/com.aspose.slides/ixamloptions/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
```

Opties die bepalen hoe een XAML-document wordt opgeslagen.

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
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Bepaalt of verborgen dia’s worden geëxporteerd. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Bepaalt of verborgen dia’s worden geëxporteerd. |
| [getOutputSaver()](#getOutputSaver--) | Vertegenwoordigt een implementatie van IOutputSaver interface. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Vertegenwoordigt een implementatie van IOutputSaver interface. |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


Bepaalt of verborgen dia’s worden geëxporteerd.

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

**Retour:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```


Bepaalt of verborgen dia’s worden geëxporteerd.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public abstract IXamlOutputSaver getOutputSaver()
```


Vertegenwoordigt een implementatie van IOutputSaver interface.

**Retour:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```


Vertegenwoordigt een implementatie van IOutputSaver interface.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |