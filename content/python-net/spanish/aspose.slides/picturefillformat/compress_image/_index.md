---
title: compress_image method
second_title: Aspose.Slides para Python mediante la API .NET
description: 
type: docs
url: /es/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Comprime la imagen reduciendo su tamaño según el tamaño de la forma y la resolución especificada. Opcionalmente, también elimina las áreas recortadas.

### Devuelve

Un **bool** que indica si la imagen se comprimió correctamente. Devuelve **True** si la imagen se redimensionó o recortó, de lo contrario **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Si es verdadero, el método eliminará las áreas recortadas de la imagen, lo que podría reducir aún más su tamaño. |
| resolution | [`PicturesCompression`](/slides/python-net/es/aspose.slides.export/picturescompression) | La resolución objetivo para la compresión, especificada como un valor del enum [`PicturesCompression`](/slides/python-net/es/aspose.slides.export/picturescompression). |

### Observaciones

Este método cambia el tamaño y la resolución de la imagen de forma similar a la función "Formato de imagen -> Comprimir imágenes" de PowerPoint.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza cuando la resolución no es un valor válido. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Comprime la imagen reduciendo su tamaño según el tamaño de la forma y la resolución especificada. Opcionalmente, también elimina las áreas recortadas.

### Devuelve

Un **bool** que indica si la imagen se comprimió correctamente. Devuelve **True** si la imagen se redimensionó o recortó, de lo contrario **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Si es verdadero, el método eliminará las áreas recortadas de la imagen, lo que podría reducir aún más su tamaño. |
| resolution | **float** | La resolución objetivo en DPI. Este valor debe ser positivo y define cómo se redimensionará la imagen. |

### Observaciones

Este método cambia el tamaño y la resolución de la imagen de forma similar a la función "Formato de imagen -> Comprimir imágenes" de PowerPoint.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza cuando la resolución no es un valor positivo. |



### Ver también
* clase [`PictureFillFormat`](/slides/python-net/es/aspose.slides/picturefillformat)
* enumeración [`PicturesCompression`](/slides/python-net/es/aspose.slides.export/picturescompression)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)