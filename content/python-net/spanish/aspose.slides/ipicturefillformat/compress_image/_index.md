---
title: compress_image method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/ipicturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Comprime la imagen reduciendo su tamaño en función del tamaño de la forma y la resolución especificada. Opcionalmente, también elimina las áreas recortadas.

### Devuelve

Un **bool** que indica si la imagen se comprimió correctamente. Devuelve **True** si la imagen se redimensionó o recortó, de lo contrario **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Si es true, el método eliminará las áreas recortadas de la imagen, reduciendo potencialmente su tamaño aún más. |
| resolution | [`PicturesCompression`](/slides/python-net/es/aspose.slides.export/picturescompression) | La resolución objetivo para la compresión, especificada como un valor del enumerado [`PicturesCompression`](/slides/python-net/es/aspose.slides.export/picturescompression). |

### Observaciones

Este método cambia el tamaño y la resolución de la imagen de manera similar a la función “Formato de imagen → Comprimir imágenes” de PowerPoint.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza cuando la resolución no es un valor válido. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Comprime la imagen reduciendo su tamaño en función del tamaño de la forma y la resolución especificada. Opcionalmente, también elimina las áreas recortadas.

### Devuelve

Un **bool** que indica si la imagen se comprimió correctamente. Devuelve **True** si la imagen se redimensionó o recortó, de lo contrario **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Si es true, el método eliminará las áreas recortadas de la imagen, reduciendo potencialmente su tamaño aún más. |
| resolution | **float** | La resolución objetivo en DPI. Este valor debe ser positivo y define cómo se redimensionará la imagen. |

### Observaciones

Este método cambia el tamaño y la resolución de la imagen de manera similar a la función “Formato de imagen → Comprimir imágenes” de PowerPoint.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza cuando la resolución no es un valor positivo. |



### Ver también
* class [`IPictureFillFormat`](/slides/python-net/es/aspose.slides/ipicturefillformat)
* enumeration [`PicturesCompression`](/slides/python-net/es/aspose.slides.export/picturescompression)
* module [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)