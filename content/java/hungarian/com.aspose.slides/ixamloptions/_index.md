---
title: IXamlOptions
second_title: Aspose.Slides Java API referencia
description: Beállítások, amelyek szabályozzák, hogyan mentődik el egy XAML dokumentum.
type: docs
url: /hu/com.aspose.slides/ixamloptions/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
```

Options that control how a XAML document is saved.

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
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Meghatározza, hogy a rejtett diák exportálva lesznek-e. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Meghatározza, hogy a rejtett diák exportálva lesznek-e. |
| [getOutputSaver()](#getOutputSaver--) | Az IOutputSaver interfész egy megvalósítását képviseli. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Az IOutputSaver interfész egy megvalósítását képviseli. |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
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

**Visszatér:**  
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
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
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public abstract IXamlOutputSaver getOutputSaver()
```

Az IOutputSaver interfész egy megvalósítását képviseli.

**Visszatér:**  
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