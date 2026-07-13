---
title: XamlOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Opties die bepalen hoe een XAML-document wordt opgeslagen.
type: docs
url: /nl/com.aspose.slides/xamloptions/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
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
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | Maakt de XamlOptions-instantie. |
## Methoden

| Method | Beschrijving |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Bepaalt of verborgen dia's worden geëxporteerd. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Bepaalt of verborgen dia's worden geëxporteerd. |
| [getOutputSaver()](#getOutputSaver--) | Vertegenwoordigt een implementatie van de IOutputSaver-interface. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Vertegenwoordigt een implementatie van de IOutputSaver-interface. |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```


Maakt de XamlOptions-instantie.

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


Bepaalt of verborgen dia's worden geëxporteerd.

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
public final void setExportHiddenSlides(boolean value)
```


Bepaalt of verborgen dia's worden geëxporteerd.

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
public final IXamlOutputSaver getOutputSaver()
```


Vertegenwoordigt een implementatie van de IOutputSaver-interface.

**Retour:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```


Vertegenwoordigt een implementatie van de IOutputSaver-interface.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |