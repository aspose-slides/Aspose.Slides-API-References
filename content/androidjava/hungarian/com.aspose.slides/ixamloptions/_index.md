---
title: IXamlOptions
second_title: Aspose.Slides Androidra a Java API hivatkozás segítségével
description: Az XAML dokumentum mentését szabályozó beállítások.
type: docs
url: /hu/com.aspose.slides/ixamloptions/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
```

Az XAML dokumentum mentését irányító beállítások.

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

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Meghatározza, hogy a rejtett diák exportálásra kerülnek-e. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Meghatározza, hogy a rejtett diák exportálásra kerülnek-e. |
| [getOutputSaver()](#getOutputSaver--) | Az IOutputSaver interfész egy megvalósítását képviseli. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Az IOutputSaver interfész egy megvalósítását képviseli. |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


Meghatározza, hogy a rejtett diák exportálásra kerülnek-e.

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
public abstract void setExportHiddenSlides(boolean value)
```


Meghatározza, hogy a rejtett diák exportálásra kerülnek-e.

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
public abstract IXamlOutputSaver getOutputSaver()
```


Az IOutputSaver interfész egy megvalósítását képviseli.

**Visszatérési érték:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```


Az IOutputSaver interfész egy megvalósítását képviseli.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |