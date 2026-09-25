---
title: get_images method
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Devuelve objetos Image para todas las diapositivas de una presentación.

### Devuelve

Objetos Image.



```python
def get_images(self, options):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones Tiff. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Devuelve objetos Thumbnail Image para diapositivas específicas de una presentación.

### Devuelve

Objetos Thumbnail Image.



```python
def get_images(self, options, slides):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones Tiff. |
| slides | **List[int]** | Arreglo con posiciones de diapositivas, comenzando desde 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Devuelve objetos Thumbnail Image para todas las diapositivas de una presentación con el tamaño especificado.

### Devuelve

Objetos Thumbnail Image.



```python
def get_images(self, options, image_size):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones Tiff. |
| image_size | [`Size`](/slides/python-net/es/aspose.slides/size) | Tamaño de la imagen a crear. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Devuelve objetos Thumbnail Image para todas las diapositivas de una presentación con escala personalizada.

### Devuelve

Objetos Thumbnail Image.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones Tiff. |
| scale_x | **float** | El valor por el cual escalar esta miniatura en la dirección del eje x. |
| scale_y | **float** | El valor por el cual escalar esta miniatura en la dirección del eje y. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
Devuelve objetos Thumbnail Image para diapositivas específicas de una presentación con el tamaño especificado.

### Devuelve

Objetos Thumbnail Image.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones Tiff. |
| slides | **List[int]** | Arreglo con posiciones de diapositivas, comenzando desde 1. |
| image_size | [`Size`](/slides/python-net/es/aspose.slides/size) | Tamaño de la imagen a crear. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Devuelve objetos Thumbnail Image para diapositivas específicas de una presentación con escala personalizada.

### Devuelve

Objetos Thumbnail Image.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones Tiff. |
| slides | **List[int]** | Arreglo con posiciones de diapositivas, comenzando desde 1. |
| scale_x | **float** | El valor por el cual escalar esta miniatura en la dirección del eje x. |
| scale_y | **float** | El valor por el cual escalar esta miniatura en la dirección del eje y. |



### See Also
* clase [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions)
* clase [`Presentation`](/slides/python-net/es/aspose.slides/presentation)
* clase [`Size`](/slides/python-net/es/aspose.slides/size)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)