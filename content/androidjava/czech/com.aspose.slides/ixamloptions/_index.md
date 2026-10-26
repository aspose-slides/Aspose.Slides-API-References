---
title: IXamlOptions
second_title: Aspose.Slides pro Android pomocí Java API
description: Možnosti, které řídí, jak je dokument XAML uložen.
type: docs
url: /cs/com.aspose.slides/ixamloptions/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
```

Možnosti, které řídí, jak je dokument XAML uložen.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pers.dispose();
>  }
> ```
## Metody

| Metoda | Popis |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Určuje, zda budou skryté snímky exportovány. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Určuje, zda budou skryté snímky exportovány. |
| [getOutputSaver()](#getOutputSaver--) | Representuje implementaci rozhraní IOutputSaver. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Representuje implementaci rozhraní IOutputSaver. |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```

Určuje, zda budou skryté snímky exportovány.

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

**Návratová hodnota:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```

Určuje, zda budou skryté snímky exportovány.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public abstract IXamlOutputSaver getOutputSaver()
```

Representuje implementaci rozhraní IOutputSaver.

**Návratová hodnota:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```

Representuje implementaci rozhraní IOutputSaver.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |