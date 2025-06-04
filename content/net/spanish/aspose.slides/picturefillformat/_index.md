---
title: PictureFillFormat
second_title: Aspose.Sildes for .NET API Reference
description: Representa un estilo de relleno de imagen.
type: docs
weight: 9120
url: /es/aspose.slides/picturefillformat/
---

## Clase PictureFillFormat

Representa un estilo de relleno de imagen.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPresentationComponent. Solo lectura [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Devuelve o establece el porcentaje de la altura real de la imagen que se recorta de la parte inferior de la imagen. Lectura/escritura Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Devuelve o establece el porcentaje de la anchura real de la imagen que se recorta del lado izquierdo de la imagen. Lectura/escritura Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Devuelve o establece el porcentaje de la anchura real de la imagen que se recorta del lado derecho de la imagen. Lectura/escritura Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Devuelve o establece el porcentaje de la altura real de la imagen que se recorta de la parte superior de la imagen. Lectura/escritura Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Devuelve o establece la dpi que se utiliza para rellenar una imagen. Lectura/escritura Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Devuelve la imagen. Solo lectura [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Devuelve o establece el modo de relleno de imagen. Lectura/escritura [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Devuelve o establece el borde inferior del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde inferior de la caja delimitadora de la forma. Un porcentaje positivo especifica un inserto, mientras que un porcentaje negativo especifica un saliente. Lectura/escritura Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Devuelve o establece el borde izquierdo del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde izquierdo de la caja delimitadora de la forma. Un porcentaje positivo especifica un inserto, mientras que un porcentaje negativo especifica un saliente. Lectura/escritura Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Devuelve o establece el borde derecho del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde derecho de la caja delimitadora de la forma. Un porcentaje positivo especifica un inserto, mientras que un porcentaje negativo especifica un saliente. Lectura/escritura Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Devuelve o establece el borde superior del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde superior de la caja delimitadora de la forma. Un porcentaje positivo especifica un inserto, mientras que un porcentaje negativo especifica un saliente. Lectura/escritura Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Devuelve o establece cómo se alinea la textura dentro de la forma. Esta configuración controla el punto de inicio del patrón de textura y cómo se repite a través de la forma. Lectura/escritura [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Voltea el mosaico de textura alrededor de su eje horizontal, vertical o ambos. Lectura/escritura [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Devuelve o establece el desplazamiento horizontal de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura hacia la derecha, mientras que un valor negativo la mueve hacia la izquierda. Lectura/escritura Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Devuelve o establece el desplazamiento vertical de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura hacia abajo, mientras que un valor negativo la mueve hacia arriba. Lectura/escritura Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Devuelve o establece la escala horizontal para el relleno de textura como un porcentaje. Lectura/escritura Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Devuelve o establece la escala vertical para el relleno de textura como un porcentaje. Lectura/escritura Single. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Comprime la imagen reduciendo su tamaño en función del tamaño de la forma y la resolución especificada. Opcionalmente, también elimina áreas recortadas. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Comprime la imagen reduciendo su tamaño en función del tamaño de la forma y la resolución especificada. Opcionalmente, también elimina áreas recortadas. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Elimina áreas recortadas del Picture de relleno. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara con el objeto especificado. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |

### Véase También

* clase [PVIObject](../pviobject)
* interfaz [IPictureFillFormat](../ipicturefillformat)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->