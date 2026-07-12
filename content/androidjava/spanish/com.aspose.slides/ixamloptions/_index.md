---
title: IXamlOptions
second_title: Aspose.Slides para Android a través de la referencia de API de Java
description: Opciones que controlan cómo se guarda un documento XAML.
type: docs
url: /es/com.aspose.slides/ixamloptions/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
```

Opciones que controlan cómo se guarda un documento XAML.

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
## Métodos

| Método | Descripción |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Determina si las diapositivas ocultas se exportarán. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Determina si las diapositivas ocultas se exportarán. |
| [getOutputSaver()](#getOutputSaver--) | Representa una implementación de la interfaz IOutputSaver. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Representa una implementación de la interfaz IOutputSaver. |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```

Determina si las diapositivas ocultas se exportarán.

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

**Devuelve:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```

Determina si las diapositivas ocultas se exportarán.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public abstract IXamlOutputSaver getOutputSaver()
```

Representa una implementación de la interfaz IOutputSaver.

**Devuelve:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```

Representa una implementación de la interfaz IOutputSaver.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |