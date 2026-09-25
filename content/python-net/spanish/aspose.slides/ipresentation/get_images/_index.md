---
title: get_images method
second_title: Aspose.Slides para Python vía .NET API Referencia
description: 
type: docs
url: /es/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Devuelve objetos de imagen en miniatura para todas las diapositivas de una presentación.

### Devuelve

Objetos Bitmap.



```python
def get_images(self, options):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de renderizado. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Devuelve objetos Bitmap en miniatura para las diapositivas especificadas de una presentación.

### Devuelve

Objetos Bitmap.



```python
def get_images(self, options, slides):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de renderizado. |
| slides | **List[int]** | Matriz con posiciones de diapositivas, comenzando en 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Devuelve objetos de imagen en miniatura para todas las diapositivas de una presentación con el tamaño especificado.

### Devuelve

Objetos Bitmap.



```python
def get_images(self, options, image_size):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de renderizado. |
| image_size | [`Size`](/slides/python-net/es/aspose.slides/size) | Tamaño de la imagen a crear. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Devuelve objetos de imagen en miniatura para todas las diapositivas de una presentación con escalado personalizado.

### Devuelve

Objetos Bitmap.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de renderizado. |
| scale_x | **float** | El valor por el cual escalar esta miniatura en la dirección del eje x. |
| scale_y | **float** | El valor por el cual escalar esta miniatura en la dirección del eje y. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
Devuelve objetos de imagen en miniatura para las diapositivas especificadas de una presentación con el tamaño especificado.

### Devuelve

Objetos Bitmap.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de renderizado. |
| slides | **List[int]** | Matriz con posiciones de diapositivas, comenzando en 1. |
| image_size | [`Size`](/slides/python-net/es/aspose.slides/size) | Tamaño de la imagen a crear. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Devuelve objetos de imagen en miniatura para las diapositivas especificadas de una presentación con escalado personalizado.

### Devuelve

Objetos Bitmap.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de renderizado. |
| slides | **List[int]** | Matriz con posiciones de diapositivas, comenzando en 1. |
| scale_x | **float** | El valor por el cual escalar esta miniatura en la dirección del eje x. |
| scale_y | **float** | El valor por el cual escalar esta miniatura en la dirección del eje y. |



### Ver también
* clase [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation)
* clase [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions)
* clase [`Size`](/slides/python-net/es/aspose.slides/size)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)