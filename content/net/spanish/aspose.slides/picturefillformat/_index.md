---
title: PictureFillFormat
second_title: Referencia de API Aspose.Sildes para .NET
description: Representa un estilo de relleno de imagen.
type: docs
weight: 9390
url: /es/aspose.slides/picturefillformat/
---
## PictureFillFormat clase

Representa un estilo de relleno de imagen.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPresentationComponent. Solo lectura [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan en la parte inferior de la imagen. Lectura/escritura Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan en el lado izquierdo de la imagen. Lectura/escritura Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan en el lado derecho de la imagen. Lectura/escritura Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan en la parte superior de la imagen. Lectura/escritura Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Devuelve o establece los dpi que se usan para rellenar una imagen. Lectura/escritura Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Devuelve la imagen. Solo lectura [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Devuelve o establece el modo de relleno de imagen. Lectura/escritura [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Devuelve o establece el borde inferior del rectángulo de relleno que se define mediante un desplazamiento de porcentaje desde el borde inferior del cuadro delimitador de la forma. Un porcentaje positivo especifica una inserción, mientras que un porcentaje negativo especifica una protrusión. Lectura/escritura Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Devuelve o establece el borde izquierdo del rectángulo de relleno que se define mediante un desplazamiento de porcentaje desde el borde izquierdo del cuadro delimitador de la forma. Un porcentaje positivo especifica una inserción, mientras que un porcentaje negativo especifica una protrusión. Lectura/escritura Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Devuelve o establece el borde derecho del rectángulo de relleno que se define mediante un desplazamiento de porcentaje desde el borde derecho del cuadro delimitador de la forma. Un porcentaje positivo especifica una inserción, mientras que un porcentaje negativo especifica una protrusión. Lectura/escritura Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Devuelve o establece el borde superior del rectángulo de relleno que se define mediante un desplazamiento de porcentaje desde el borde superior del cuadro delimitador de la forma. Un porcentaje positivo especifica una inserción, mientras que un porcentaje negativo especifica una protrusión. Lectura/escritura Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Devuelve o establece cómo se alinea la textura dentro de la forma. Esta configuración controla el punto de inicio del patrón de textura y cómo se repite a lo largo de la forma. Lectura/escritura [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Voltea el mosaico de textura en su eje horizontal, vertical o ambos. Lectura/escritura [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Devuelve o establece el desplazamiento horizontal de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura a la derecha, mientras que un valor negativo la mueve a la izquierda. Lectura/escritura Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Devuelve o establece el desplazamiento vertical de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura hacia abajo, mientras que un valor negativo la mueve hacia arriba. Lectura/escritura Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Devuelve o establece la escala horizontal para el relleno de textura como un porcentaje. Lectura/escritura Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Devuelve o establece la escala vertical para el relleno de textura como un porcentaje. Lectura/escritura Single. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Comprime la imagen reduciendo su tamaño en función del tamaño de la forma y la resolución especificada. Opcionalmente, también elimina áreas recortadas. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Comprime la imagen reduciendo su tamaño en función del tamaño de la forma y la resolución especificada. Opcionalmente, también elimina áreas recortadas. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Elimina áreas recortadas de la Imagen de relleno. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara con el objeto especificado. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |

### Ver también

* clase [PVIObject](../pviobject)
* interfaz [IPictureFillFormat](../ipicturefillformat)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->