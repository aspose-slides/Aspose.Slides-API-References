---
title: IXamlOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Alternativ som styr hur ett XAML-dokument sparas.
type: docs
url: /sv/com.aspose.slides/ixamloptions/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
```

Alternativ som styr hur ett XAML-dokument sparas.

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
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Bestämmer om dolda bilder ska exporteras. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Bestämmer om dolda bilder ska exporteras. |
| [getOutputSaver()](#getOutputSaver--) | Representerar en implementation av IOutputSaver-gränssnittet. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Representerar en implementation av IOutputSaver-gränssnittet. |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


Bestämmer om dolda bilder ska exporteras.

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

**Returnerar:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```


Bestämmer om dolda bilder ska exporteras.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public abstract IXamlOutputSaver getOutputSaver()
```


Representerar en implementation av IOutputSaver-gränssnittet.

**Returnerar:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```


Representerar en implementation av IOutputSaver-gränssnittet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |