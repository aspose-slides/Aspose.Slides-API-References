---
title: IPictureFillFormat
second_title: Referencia de la API Aspose.Slides para .NET
description: Representa un estilo de relleno de imagen.
type: docs
weight: 6450
url: /es/aspose.slides/ipicturefillformat/
---

## Interfaz IPictureFillFormat

Representa un estilo de relleno de imagen.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Permite obtener la interfaz base IFillParamSource. Solo lectura [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan en la parte inferior de la imagen. Lectura/escritura Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan en la izquierda de la imagen. Lectura/escritura Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan en la derecha de la imagen. Lectura/escritura Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan en la parte superior de la imagen. Lectura/escritura Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Devuelve o establece el dpi que se utiliza para rellenar una imagen. Lectura/escritura Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Devuelve la imagen. Solo lectura [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Devuelve o establece el modo de relleno de la imagen. Lectura/escritura [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Devuelve o establece el borde inferior del rectángulo de relleno que se define por un desplazamiento porcentual desde el borde inferior del cuadro delimitador de la forma. Un porcentaje positivo especifica un interno, mientras que un porcentaje negativo especifica un externo. Lectura/escritura Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Devuelve o establece el borde izquierdo del rectángulo de relleno que se define por un desplazamiento porcentual desde el borde izquierdo del cuadro delimitador de la forma. Un porcentaje positivo especifica un interno, mientras que un porcentaje negativo especifica un externo. Lectura/escritura Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Devuelve o establece el borde derecho del rectángulo de relleno que se define por un desplazamiento porcentual desde el borde derecho del cuadro delimitador de la forma. Un porcentaje positivo especifica un interno, mientras que un porcentaje negativo especifica un externo. Lectura/escritura Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Devuelve o establece el borde superior del rectángulo de relleno que se define por un desplazamiento porcentual desde el borde superior del cuadro delimitador de la forma. Un porcentaje positivo especifica un interno, mientras que un porcentaje negativo especifica un externo. Lectura/escritura Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Devuelve o establece cómo se alinea la textura dentro de la forma. Esta configuración controla el punto de inicio del patrón de textura y cómo se repite a través de la forma. Lectura/escritura [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Voltea la loseta de textura alrededor de su eje horizontal, vertical o ambos. Lectura/escritura [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Devuelve o establece el desplazamiento horizontal de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura a la derecha, mientras que un valor negativo la mueve a la izquierda. Lectura/escritura Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Devuelve o establece el desplazamiento vertical de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura hacia abajo, mientras que un valor negativo la mueve hacia arriba. Lectura/escritura Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Devuelve o establece la escala horizontal para el relleno de textura como un porcentaje. Lectura/escritura Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Devuelve o establece la escala vertical para el relleno de textura como un porcentaje. Lectura/escritura Single. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Comprime la imagen reduciendo su tamaño basado en el tamaño de la forma y la resolución especificada. Opcionalmente, también elimina áreas recortadas. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Comprime la imagen reduciendo su tamaño basado en el tamaño de la forma y la resolución especificada. Opcionalmente, también elimina áreas recortadas. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Elimina áreas recortadas del Picture de relleno. |

### Ver También

* interfaz [IFillParamSource](../ifillparamsource)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->