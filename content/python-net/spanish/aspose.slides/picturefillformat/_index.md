---
title: PictureFillFormat class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/picturefillformat/
---
## PictureFillFormat clase

Representa un estilo de relleno con imagen.

**Inheritance:**[`PictureFillFormat`](/slides/python-net/es/aspose.slides/picturefillformat) → [`PVIObject`](/slides/python-net/es/aspose.slides/pviobject)

El tipo PictureFillFormat expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`dpi`](/slides/python-net/es/aspose.slides/picturefillformat/dpi/) | Devuelve o establece los dpi que se usan para rellenar una imagen.<br/>            Lectura/escritura **int**. |
| [`picture_fill_mode`](/slides/python-net/es/aspose.slides/picturefillformat/picture_fill_mode/) | Devuelve o establece el modo de relleno de imagen.<br/>            Lectura/escritura [`PictureFillMode`](/slides/python-net/es/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/es/aspose.slides/picturefillformat/picture/) | Devuelve la imagen.<br/>            Solo lectura [`ISlidesPicture`](/slides/python-net/es/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/es/aspose.slides/picturefillformat/crop_left/) | Devuelve o establece el número de por ciento del ancho real de la imagen que se recorta<br/>            en el lado izquierdo de la imagen. <br/>            Lectura/escritura **float**. |
| [`crop_top`](/slides/python-net/es/aspose.slides/picturefillformat/crop_top/) | Devuelve o establece el número de por ciento de la altura real de la imagen que se recorta<br/>            en la parte superior de la imagen. <br/>            Lectura/escritura **float**. |
| [`crop_right`](/slides/python-net/es/aspose.slides/picturefillformat/crop_right/) | Devuelve o establece el número de por ciento del ancho real de la imagen que se recorta<br/>            en el lado derecho de la imagen. <br/>            Lectura/escritura **float**. |
| [`crop_bottom`](/slides/python-net/es/aspose.slides/picturefillformat/crop_bottom/) | Devuelve o establece el número de por ciento de la altura real de la imagen que se recorta<br/>            en la parte inferior de la imagen. <br/>            Lectura/escritura **float**. |
| [`stretch_offset_left`](/slides/python-net/es/aspose.slides/picturefillformat/stretch_offset_left/) | Devuelve o establece el borde izquierdo del rectángulo de relleno que se define mediante un desplazamiento de porcentaje <br/>            desde el borde izquierdo del cuadro delimitador de la forma. <br/>            Un porcentaje positivo especifica una inserción, mientras que un porcentaje negativo especifica una salida.<br/>            Lectura/escritura **float**. |
| [`stretch_offset_top`](/slides/python-net/es/aspose.slides/picturefillformat/stretch_offset_top/) | Devuelve o establece el borde superior del rectángulo de relleno que se define mediante un desplazamiento de porcentaje <br/>            desde el borde superior del cuadro delimitador de la forma. <br/>            Un porcentaje positivo especifica una inserción, mientras que un porcentaje negativo especifica una salida.<br/>            Lectura/escritura **float**. |
| [`stretch_offset_right`](/slides/python-net/es/aspose.slides/picturefillformat/stretch_offset_right/) | Devuelve o establece el borde derecho del rectángulo de relleno que se define mediante un desplazamiento de porcentaje <br/>            desde el borde derecho del cuadro delimitador de la forma. <br/>            Un porcentaje positivo especifica una inserción, mientras que un porcentaje negativo especifica una salida.<br/>            Lectura/escritura **float**. |
| [`stretch_offset_bottom`](/slides/python-net/es/aspose.slides/picturefillformat/stretch_offset_bottom/) | Devuelve o establece el borde inferior del rectángulo de relleno que se define mediante un desplazamiento de porcentaje <br/>            desde el borde inferior del cuadro delimitador de la forma. <br/>            Un porcentaje positivo especifica una inserción, mientras que un porcentaje negativo especifica una salida.<br/>            Lectura/escritura **float**. |
| [`tile_offset_x`](/slides/python-net/es/aspose.slides/picturefillformat/tile_offset_x/) | Devuelve o establece el desplazamiento horizontal de la textura desde el origen de la forma en puntos.<br/>             Un valor positivo mueve la textura a la derecha, mientras que un valor negativo la mueve a la izquierda.<br/>             Lectura/escritura **float**. |
| [`tile_offset_y`](/slides/python-net/es/aspose.slides/picturefillformat/tile_offset_y/) | Devuelve o establece el desplazamiento vertical de la textura desde el origen de la forma en puntos.<br/>             Un valor positivo mueve la textura hacia abajo, mientras que un valor negativo la mueve hacia arriba.<br/>             Lectura/escritura **float**. |
| [`tile_scale_x`](/slides/python-net/es/aspose.slides/picturefillformat/tile_scale_x/) | Devuelve o establece la escala horizontal para el relleno de textura como porcentaje.<br/>             Lectura/escritura **float**. |
| [`tile_scale_y`](/slides/python-net/es/aspose.slides/picturefillformat/tile_scale_y/) | Devuelve o establece la escala vertical para el relleno de textura como porcentaje.<br/>             Lectura/escritura **float**. |
| [`tile_alignment`](/slides/python-net/es/aspose.slides/picturefillformat/tile_alignment/) | Devuelve o establece cómo se alinea la textura dentro de la forma. Esta configuración controla el punto de partida del patrón de textura y cómo se repite a lo largo de la forma.<br/>             Lectura/escritura [`RectangleAlignment`](/slides/python-net/es/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/es/aspose.slides/picturefillformat/tile_flip/) | Invierte el mosaico de textura alrededor de su eje horizontal, vertical o ambos.<br/>             Lectura/escritura [`TileFlip`](/slides/python-net/es/aspose.slides/tileflip). |
| [`slide`](/slides/python-net/es/aspose.slides/picturefillformat/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides/picturefillformat/presentation/) |  |

## Métodos

| Method | Description |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/es/aspose.slides/picturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | Comprime la imagen reduciendo su tamaño según el tamaño de la forma y la resolución especificada. Opcionalmente, también elimina áreas recortadas. |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/es/aspose.slides/picturefillformat/compress_image/#bool-float) | Comprime la imagen reduciendo su tamaño según el tamaño de la forma y la resolución especificada. Opcionalmente, también elimina áreas recortadas. |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/es/aspose.slides/picturefillformat/delete_picture_cropped_areas/#) | Elimina áreas recortadas del Picture de relleno. |


### Ver también
* clase [`PictureFillFormat`](/slides/python-net/es/aspose.slides/picturefillformat)
* clase [`PVIObject`](/slides/python-net/es/aspose.slides/pviobject)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)