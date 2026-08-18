---
title: SlideImageFormat
second_title: Referencia de API de Aspose.Slides para Java
description: Determina el formato en el que se guardará la imagen de la diapositiva para la presentación en la exportación HTML.
type: docs
url: /es/com.aspose.slides/slideimageformat/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

Determina el formato en el que la imagen de la diapositiva se guardará para la presentación en la exportación HTML.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Las diapositivas deben convertirse a un formato SVG. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Las diapositivas deben convertirse a una imagen rasterizada. |
### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```

### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```

Las diapositivas deben convertirse a un formato SVG.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | Opciones para la exportación SVG. |

**Devuelve:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - El objeto [SlideImageFormat](../../com.aspose.slides/slideimageformat).
### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

Las diapositivas deben convertirse a una imagen rasterizada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scale | float | El factor por el cual escalar la imagen de salida. |
| imageFormat | int | El formato de la imagen resultante (p. ej., PNG, JPEG). |

**Devuelve:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -