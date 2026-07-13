---
title: XamlOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Alternativ som styr hur ett XAML-dokument sparas.
type: docs
url: /sv/com.aspose.slides/xamloptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
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
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | Skapar XamlOptions-instansen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Avgör om dolda bilder ska exporteras. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Avgör om dolda bilder ska exporteras. |
| [getOutputSaver()](#getOutputSaver--) | Representerar en implementation av IOutputSaver-gränssnittet. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Representerar en implementation av IOutputSaver-gränssnittet. |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```


Skapar XamlOptions-instansen.

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


Avgör om dolda bilder ska exporteras.

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
public final void setExportHiddenSlides(boolean value)
```


Avgör om dolda bilder ska exporteras.

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
public final IXamlOutputSaver getOutputSaver()
```


Representerar en implementation av IOutputSaver-gränssnittet.

**Returnerar:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```


Representerar en implementation av IOutputSaver-gränssnittet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |