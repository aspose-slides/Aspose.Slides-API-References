---
title: XpsOptions
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Proporciona opciones que controlan cómo se guarda una presentación en formato XPS.
type: docs
url: /es/com.aspose.slides/xpsoptions/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas las interfaces implementadas:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Proporciona opciones que controlan cómo se guarda una presentación en formato XPS.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Instanciar un objeto Presentation que representa un archivo de presentación
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // Guardar la presentación en un documento XPS
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // Instanciar un objeto Presentation que representa un archivo de presentación
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // Instanciar la clase TiffOptions
>      XpsOptions options = new XpsOptions();
>      // Guardar MetaFiles como PNG
>      options.setSaveMetafilesAsPng(true);
>      // Guardar la presentación en un documento XPS
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructores

| Constructor | Descripción |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | Constructor predeterminado. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Verdadero para convertir todos los metarchivos utilizados en una presentación a imágenes PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Verdadero para convertir todos los metarchivos utilizados en una presentación a imágenes PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Verdadero para dibujar un marco negro alrededor de cada diapositiva. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Verdadero para dibujar un marco negro alrededor de cada diapositiva. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```


Constructor predeterminado.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es **false**.

**Devuelve:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es **false**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```


Verdadero para convertir todos los metarchivos utilizados en una presentación a imágenes PNG. Booleano de lectura/escritura.

--------------------

El valor predeterminado es **true**.

**Devuelve:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```


Verdadero para convertir todos los metarchivos utilizados en una presentación a imágenes PNG. Booleano de lectura/escritura.

--------------------

El valor predeterminado es **true**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```


Verdadero para dibujar un marco negro alrededor de cada diapositiva. Booleano de lectura/escritura.

--------------------

El valor predeterminado es **false**.

**Devuelve:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```


Verdadero para dibujar un marco negro alrededor de cada diapositiva. Booleano de lectura/escritura.

--------------------

El valor predeterminado es **false**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |