---
title: XamlOptions
second_title: Aspose.Slides dla Androida poprzez odwołanie do dokumentacji API Java
description: Opcje kontrolujące sposób zapisywania dokumentu XAML.
type: docs
url: /pl/com.aspose.slides/xamloptions/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
```

Opcje kontrolujące sposób zapisywania dokumentu XAML.

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
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | Tworzy instancję XamlOptions. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Określa, czy ukryte slajdy zostaną wyeksportowane. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Określa, czy ukryte slajdy zostaną wyeksportowane. |
| [getOutputSaver()](#getOutputSaver--) | Reprezentuje implementację interfejsu IOutputSaver. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Reprezentuje implementację interfejsu IOutputSaver. |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```

Tworzy instancję XamlOptions.

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

Określa, czy ukryte slajdy zostaną wyeksportowane.

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

**Zwraca:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

Określa, czy ukryte slajdy zostaną wyeksportowane.

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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public final IXamlOutputSaver getOutputSaver()
```

Reprezentuje implementację interfejsu IOutputSaver.

**Zwraca:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```

Reprezentuje implementację interfejsu IOutputSaver.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |