---
title: XamlOptions
second_title: Aspose.Slides Androidhoz a Java API hivatkozás alapján
description: Az XAML dokumentum mentésének módját vezérlő beállítások.
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

Az XAML dokumentum mentésének vezérlésére szolgáló beállítások.

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

| Konstruktor | Leírás |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | Létrehozza a XamlOptions példányt. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Megállapítja, hogy a rejtett diák exportálásra kerülnek-e. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Megállapítja, hogy a rejtett diák exportálásra kerülnek-e. |
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

Megállapítja, hogy a rejtett diák exportálásra kerülnek-e.

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

Megállapítja, hogy a rejtett diák exportálásra kerülnek-e.

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
| Paraméter | Típus | Leírás |
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
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |