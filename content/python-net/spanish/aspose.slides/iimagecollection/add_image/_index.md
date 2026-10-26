---
title: add_image method
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/iimagecollection/add_image/
weight: 10
---
## add_image(self, image) {#iimage}
Agregar una imagen a una presentación.

### Devuelve

Imagen agregada.



```python
def add_image(self, image):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/es/aspose.slides/iimage) | Imagen a agregar. |

### Observaciones

Este método convierte metaficheros WMF/EMF a imagen PNG raster antes de insertarlos en una presentación.


## add_image(self, stream) {#iorawiobase}
Agregar una imagen a una presentación desde un flujo.

### Devuelve

Imagen agregada.



```python
def add_image(self, stream):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flujo desde el cual agregar la imagen. |

### Observaciones

Este método puede agregar metaficheros WMF/EMF a una presentación sin convertirlos a imagen PNG raster.


## add_image(self, buffer) {#bytes}
Agregar una imagen a una presentación desde un búfer especificado.

### Devuelve

Imagen agregada.



```python
def add_image(self, buffer):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| buffer | **bytes** | Búfer. |


## add_image(self, image_source) {#ippimage}
Agregar una copia de una imagen desde otra presentación.

### Devuelve

Imagen agregada.



```python
def add_image(self, image_source):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage) | Imagen de origen. |


## add_image(self, svg_image) {#isvgimage}
Agregar una imagen a una presentación desde un objeto SVG.

### Devuelve

Imagen agregada.



```python
def add_image(self, svg_image):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/es/aspose.slides/isvgimage) | Objeto de imagen SVG [`ISvgImage`](/slides/python-net/es/aspose.slides/isvgimage) |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Se lanza cuando el parámetro svgImage es None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Crea y agrega una imagen a una presentación desde un flujo.

### Devuelve

[`IPPImage`](/slides/python-net/es/aspose.slides/ippimage) agregado.



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flujo desde el cual agregar el archivo de imagen. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/es/aspose.slides/loadingstreambehavior) | El comportamiento que se aplicará al flujo. |



### Véase también
* clase [`IImage`](/slides/python-net/es/aspose.slides/iimage)
* clase [`IImageCollection`](/slides/python-net/es/aspose.slides/iimagecollection)
* clase [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage)
* clase [`ISvgImage`](/slides/python-net/es/aspose.slides/isvgimage)
* enumeración [`LoadingStreamBehavior`](/slides/python-net/es/aspose.slides/loadingstreambehavior)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)