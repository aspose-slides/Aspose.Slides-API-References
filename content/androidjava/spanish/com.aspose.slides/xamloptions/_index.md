---
title: XamlOptions
second_title: Referencia de API Java de Aspose.Slides para Android
description: Opciones que controlan cómo se guarda un documento XAML.
type: docs
url: /es/com.aspose.slides/xamloptions/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas las interfaces implementadas:**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
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
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | Crea la instancia de XamlOptions. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Determina si las diapositivas ocultas se exportarán. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Determina si las diapositivas ocultas se exportarán. |
| [getOutputSaver()](#getOutputSaver--) | Representa una implementación de la interfaz IOutputSaver. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Representa una implementación de la interfaz IOutputSaver. |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```

Crea la instancia de XamlOptions.

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
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
public final void setExportHiddenSlides(boolean value)
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
public final IXamlOutputSaver getOutputSaver()
```

Representa una implementación de la interfaz IOutputSaver.

**Devuelve:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```

Representa una implementación de la interfaz IOutputSaver.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |