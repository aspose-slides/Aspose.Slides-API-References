---
title: get_image method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/islide/get_image/
weight: 40
---
## get_image(self) {#}
Devuelve un objeto Image Thumbnail (20 % del tamaño real).

### Returns

Objeto Image **aspose.slides.IImage**



```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
Devuelve un objeto de imagen con el tamaño especificado.

### Returns

Objeto Bitmap.



```python
def get_image(self, image_size):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/es/aspose.slides/size) | Tamaño de la imagen a crear. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Devuelve un objeto bitmap tiff Thumbnail con los parámetros especificados.

### Returns

Objeto Image.



```python
def get_image(self, options):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/es/aspose.slides.export/itiffoptions) | Opciones Tiff. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Devuelve un objeto Bitmap Thumbnail.

### Returns

Objetos Bitmap.



```python
def get_image(self, options):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de renderizado. |


## get_image(self, scale_x, scale_y) {#float-float}
Devuelve un objeto de imagen con escalado personalizado.

### Returns

Objeto Image **aspose.slides.IImage**



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scale_x | **float** | El valor por el cual escalar este Thumbnail en la dirección del eje x. |
| scale_y | **float** | El valor por el cual escalar este Thumbnail en la dirección del eje y. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Devuelve un objeto Bitmap Thumbnail con el tamaño especificado.

### Returns

Objetos Bitmap.



```python
def get_image(self, options, image_size):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de renderizado. |
| image_size | [`Size`](/slides/python-net/es/aspose.slides/size) | Tamaño de la imagen a crear. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Devuelve un objeto Bitmap Thumbnail con escalado personalizado.

### Returns

Objetos Bitmap.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de renderizado. |
| scale_x | **float** | El valor por el cual escalar este Thumbnail en la dirección del eje x. |
| scale_y | **float** | El valor por el cual escalar este Thumbnail en la dirección del eje y. |



### Ver también
* clase [`IImage`](/slides/python-net/es/aspose.slides/iimage)
* clase [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions)
* clase [`ISlide`](/slides/python-net/es/aspose.slides/islide)
* clase [`ITiffOptions`](/slides/python-net/es/aspose.slides.export/itiffoptions)
* clase [`Size`](/slides/python-net/es/aspose.slides/size)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)