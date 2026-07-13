---
title: IXamlOptions
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Opcje kontrolujące sposób zapisywania dokumentu XAML.
type: docs
url: /pl/com.aspose.slides/ixamloptions/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
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

## Metody

| Metoda | Opis |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Określa, czy ukryte slajdy będą eksportowane. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Określa, czy ukryte slajdy będą eksportowane. |
| [getOutputSaver()](#getOutputSaver--) | Reprezentuje implementację interfejsu IOutputSaver. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Reprezentuje implementację interfejsu IOutputSaver. |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


Określa, czy ukryte slajdy będą eksportowane.

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
public abstract void setExportHiddenSlides(boolean value)
```


Określa, czy ukryte slajdy będą eksportowane.

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
public abstract IXamlOutputSaver getOutputSaver()
```


Reprezentuje implementację interfejsu IOutputSaver.

**Zwraca:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```


Reprezentuje implementację interfejsu IOutputSaver.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |