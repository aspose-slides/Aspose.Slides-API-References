---
title: XamlOptions
second_title: Aspose.Slides Java API referencia
description: A XAML dokumentum mentését szabályozó beállítások.
type: docs
url: /hu/com.aspose.slides/xamloptions/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Minden megvalósított interfész:**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
```

Az XAML dokumentum mentését szabályozó beállítások.

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
## Konstruktorok

| Constructor | Description |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | Létrehozza a XamlOptions példányt. |
## Módszerek

| Method | Description |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Meghatározza, hogy a rejtett diák exportálva lesznek-e. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Meghatározza, hogy a rejtett diák exportálva lesznek-e. |
| [getOutputSaver()](#getOutputSaver--) | Az IOutputSaver interfész egy megvalósítását képviseli. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Az IOutputSaver interfész egy megvalósítását képviseli. |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```


Létrehozza a XamlOptions példányt.

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


Meghatározza, hogy a rejtett diák exportálva lesznek-e.

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

**Visszatérési érték:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```


Meghatározza, hogy a rejtett diák exportálva lesznek-e.

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

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public final IXamlOutputSaver getOutputSaver()
```


Az IOutputSaver interfész egy megvalósítását képviseli.

**Visszatérési érték:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```


Az IOutputSaver interfész egy megvalósítását képviseli.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |