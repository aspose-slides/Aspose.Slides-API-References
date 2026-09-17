---
title: add_image method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/imagecollection/add_image/
weight: 10
---
## add_image(self, image_source) {#ippimage}
Añade una copia de una imagen de otra presentación.

### Devuelve

Imagen añadida.



```python
def add_image(self, image_source):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage) | Imagen de origen. |


## add_image(self, image) {#iimage}
Añade una imagen a una presentación.

### Devuelve

Imagen añadida.



```python
def add_image(self, image):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/es/aspose.slides/iimage) | Imagen a añadir. |

### Observaciones

Este método convierte archivos metafile WMF/EMF a imagen PNG raster antes de insertarla en una presentación.


## add_image(self, stream) {#iorawiobase}
Añade una imagen a una presentación desde un flujo.

### Devuelve

Imagen añadida.



```python
def add_image(self, stream):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flujo del cual se agrega la imagen. |

### Observaciones

Este método puede agregar archivos metafile WMF/EMF a una presentación sin convertirlos a imagen PNG raster.


## add_image(self, buffer) {#bytes}
Añade una imagen a una presentación desde un búfer especificado.

### Devuelve

Imagen añadida.



```python
def add_image(self, buffer):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| buffer | **bytes** | Búfer. |


## add_image(self, svg_image) {#isvgimage}
Añade una imagen a una presentación desde un objeto Svg.

### Devuelve

Imagen añadida.



```python
def add_image(self, svg_image):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/es/aspose.slides/isvgimage) | Objeto de imagen Svg [`ISvgImage`](/slides/python-net/es/aspose.slides/isvgimage) |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Cuando el parámetro svgImage es None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Crea y añade una imagen a una presentación desde un flujo.

### Devuelve

Añadido [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flujo del que se añade el archivo de imagen. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/es/aspose.slides/loadingstreambehavior) | El comportamiento que se aplicará al flujo. |



### Ver también
* clase [`IImage`](/slides/python-net/es/aspose.slides/iimage)
* clase [`ImageCollection`](/slides/python-net/es/aspose.slides/imagecollection)
* clase [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage)
* clase [`ISvgImage`](/slides/python-net/es/aspose.slides/isvgimage)
* enumeración [`LoadingStreamBehavior`](/slides/python-net/es/aspose.slides/loadingstreambehavior)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)