---
title: IPictureFillFormat class
second_title: Aspose.Slides para Python mediante la API de .NET
description: 
type: docs
url: /es/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat clase

Representa un estilo de relleno de imagen.

El tipo IPictureFillFormat expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`dpi`](/slides/python-net/es/aspose.slides/ipicturefillformat/dpi/) | Devuelve o establece los dpi que se utilizan para rellenar una imagen.<br/>            Lectura/escritura **int**. |
| [`picture_fill_mode`](/slides/python-net/es/aspose.slides/ipicturefillformat/picture_fill_mode/) | Devuelve o establece el modo de relleno de imagen.<br/>            Lectura/escritura [`PictureFillMode`](/slides/python-net/es/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/es/aspose.slides/ipicturefillformat/picture/) | Devuelve la imagen.<br/>            Solo lectura [`ISlidesPicture`](/slides/python-net/es/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/es/aspose.slides/ipicturefillformat/crop_left/) | Devuelve o establece el número de porcentaje del ancho real de la imagen que se recorta<br/>            a la izquierda de la imagen. <br/>            Lectura/escritura **float**. |
| [`crop_top`](/slides/python-net/es/aspose.slides/ipicturefillformat/crop_top/) | Devuelve o establece el número de porcentaje de la altura real de la imagen que se recorta<br/>            la parte superior de la imagen. <br/>            Lectura/escritura **float**. |
| [`crop_right`](/slides/python-net/es/aspose.slides/ipicturefillformat/crop_right/) | Devuelve o establece el número de porcentaje del ancho real de la imagen que se recorta<br/>            a la derecha de la imagen. <br/>            Lectura/escritura **float**. |
| [`crop_bottom`](/slides/python-net/es/aspose.slides/ipicturefillformat/crop_bottom/) | Devuelve o establece el número de porcentaje de la altura real de la imagen que se recorta<br/>            la parte inferior de la imagen. <br/>            Lectura/escritura **float**. |
| [`stretch_offset_left`](/slides/python-net/es/aspose.slides/ipicturefillformat/stretch_offset_left/) | Devuelve o establece el borde izquierdo del rectángulo de relleno que está definido por un desplazamiento de porcentaje <br/>            desde el borde izquierdo del cuadro delimitador de la forma. <br/>            Un porcentaje positivo indica una inserción, mientras que un porcentaje negativo indica una proyección.<br/>            Lectura/escritura **float**. |
| [`stretch_offset_top`](/slides/python-net/es/aspose.slides/ipicturefillformat/stretch_offset_top/) | Devuelve o establece el borde superior del rectángulo de relleno que está definido por un desplazamiento de porcentaje <br/>            desde el borde superior del cuadro delimitador de la forma. <br/>            Un porcentaje positivo indica una inserción, mientras que un porcentaje negativo indica una proyección.<br/>            Lectura/escritura **float**. |
| [`stretch_offset_right`](/slides/python-net/es/aspose.slides/ipicturefillformat/stretch_offset_right/) | Devuelve o establece el borde derecho del rectángulo de relleno que está definido por un desplazamiento de porcentaje <br/>            desde el borde derecho del cuadro delimitador de la forma. <br/>            Un porcentaje positivo indica una inserción, mientras que un porcentaje negativo indica una proyección.<br/>            Lectura/escritura **float**. |
| [`stretch_offset_bottom`](/slides/python-net/es/aspose.slides/ipicturefillformat/stretch_offset_bottom/) | Devuelve o establece el borde inferior del rectángulo de relleno que está definido por un desplazamiento de porcentaje <br/>            desde el borde inferior del cuadro delimitador de la forma. <br/>            Un porcentaje positivo indica una inserción, mientras que un porcentaje negativo indica una proyección.<br/>            Lectura/escritura **float**. |
| [`tile_offset_x`](/slides/python-net/es/aspose.slides/ipicturefillformat/tile_offset_x/) | Devuelve o establece el desplazamiento horizontal de la textura desde el origen de la forma en puntos.<br/>             Un valor positivo mueve la textura a la derecha, mientras que un valor negativo la mueve a la izquierda.<br/>             Lectura/escritura **float**. |
| [`tile_offset_y`](/slides/python-net/es/aspose.slides/ipicturefillformat/tile_offset_y/) | Devuelve o establece el desplazamiento vertical de la textura desde el origen de la forma en puntos.<br/>             Un valor positivo mueve la textura hacia abajo, mientras que un valor negativo la mueve hacia arriba.<br/>             Lectura/escritura **float**. |
| [`tile_scale_x`](/slides/python-net/es/aspose.slides/ipicturefillformat/tile_scale_x/) | Devuelve o establece la escala horizontal para el relleno de textura como porcentaje.<br/>             Lectura/escritura **float**. |
| [`tile_scale_y`](/slides/python-net/es/aspose.slides/ipicturefillformat/tile_scale_y/) | Devuelve o establece la escala vertical para el relleno de textura como porcentaje.<br/>             Lectura/escritura **float**. |
| [`tile_alignment`](/slides/python-net/es/aspose.slides/ipicturefillformat/tile_alignment/) | Devuelve o establece cómo se alinea la textura dentro de la forma. Esta configuración controla el punto de inicio del patrón de textura y cómo se repite a través de la forma.<br/>             Lectura/escritura [`RectangleAlignment`](/slides/python-net/es/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/es/aspose.slides/ipicturefillformat/tile_flip/) | Invierte el mosaico de textura alrededor de su eje horizontal, vertical o ambos.<br/>             Lectura/escritura [`TileFlip`](/slides/python-net/es/aspose.slides/tileflip). |

## Métodos

| Método | Descripción |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/es/aspose.slides/ipicturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | Comprime la imagen reduciendo su tamaño según el tamaño de la forma y la resolución especificada. Opcionalmente, también elimina las áreas recortadas. |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/es/aspose.slides/ipicturefillformat/compress_image/#bool-float) | Comprime la imagen reduciendo su tamaño según el tamaño de la forma y la resolución especificada. Opcionalmente, también elimina las áreas recortadas. |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/es/aspose.slides/ipicturefillformat/delete_picture_cropped_areas/#) | Elimina áreas recortadas del Picture de relleno. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)