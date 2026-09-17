---
title: get_images method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
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
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de Tiff. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Devuelve objetos Thumbnail Image para las diapositivas especificadas de una presentación.

### Devuelve

Objetos Image.



```python
def get_images(self, options, slides):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de Tiff. |
| slides | **List[int]** | Matriz con las posiciones de las diapositivas, comenzando desde 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Devuelve objetos Thumbnail Image para todas las diapositivas de una presentación con el tamaño especificado.

### Devuelve

Objetos Image.



```python
def get_images(self, options, image_size):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de Tiff. |
| image_size | **aspose.slides.Size** | Tamaño de la imagen a crear. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Devuelve objetos Thumbnail Image para todas las diapositivas de una presentación con escalado personalizado.

### Devuelve

Objetos Image.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de Tiff. |
| scale_x | **float** | El valor por el cual escalar esta miniatura en la dirección del eje x. |
| scale_y | **float** | El valor por el cual escalar esta miniatura en la dirección del eje y. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Devuelve objetos Thumbnail Image para las diapositivas especificadas de una presentación con el tamaño especificado.

### Devuelve

Objetos Image.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de Tiff. |
| slides | **List[int]** | Matriz con las posiciones de las diapositivas, comenzando desde 1. |
| image_size | **aspose.slides.Size** | Tamaño de la imagen a crear. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Devuelve objetos Thumbnail Image para las diapositivas especificadas de una presentación con escalado personalizado.

### Devuelve

Objetos Image.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de Tiff. |
| slides | **List[int]** | Matriz con las posiciones de las diapositivas, comenzando desde 1. |
| scale_x | **float** | El valor por el cual escalar esta miniatura en la dirección del eje x. |
| scale_y | **float** | El valor por el cual escalar esta miniatura en la dirección del eje y. |



### Ver también
* clase [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions)
* clase [`Presentation`](/slides/python-net/es/aspose.slides/presentation)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)