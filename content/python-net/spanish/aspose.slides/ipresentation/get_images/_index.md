---
title: get_images method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
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
Devuelve objetos Bitmap en miniatura para diapositivas especificadas de una presentación.

### Devuelve

Objetos Bitmap.



```python
def get_images(self, options, slides):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de renderizado. |
| slides | **List[int]** | Arreglo con posiciones de diapositivas, comenzando desde 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
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
| image_size | **aspose.slides.Size** | Tamaño de la imagen a crear. |


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


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Devuelve objetos de imagen en miniatura para diapositivas especificadas de una presentación con el tamaño especificado.

### Devuelve

Objetos Bitmap.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de renderizado. |
| slides | **List[int]** | Arreglo con posiciones de diapositivas, comenzando desde 1. |
| image_size | **aspose.slides.Size** | Tamaño de la imagen a crear. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Devuelve objetos de imagen en miniatura para diapositivas especificadas de una presentación con escalado personalizado.

### Devuelve

Objetos Bitmap.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de renderizado. |
| slides | **List[int]** | Arreglo con posiciones de diapositivas, comenzando desde 1. |
| scale_x | **float** | El valor por el cual escalar esta miniatura en la dirección del eje x. |
| scale_y | **float** | El valor por el cual escalar esta miniatura en la dirección del eje y. |



### Ver también
* clase [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation)
* clase [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)