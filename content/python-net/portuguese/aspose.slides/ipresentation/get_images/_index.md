---
title: get_images method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Retorna objetos Thumbnail Image para todos os slides de uma apresentação.

### Retorna

Bitmap objects.



```python
def get_images(self, options):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions) | Rendering options. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Retorna objetos Thumbnail Bitmap para slides especificados de uma apresentação.

### Retorna

Bitmap objects.



```python
def get_images(self, options, slides):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Retorna objetos Thumbnail Image para todos os slides de uma apresentação com tamanho especificado.

### Retorna

Bitmap objects.



```python
def get_images(self, options, image_size):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions) | Rendering options. |
| image_size | [`Size`](/slides/python-net/pt/aspose.slides/size) | Size of the image to create. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Retorna objetos Thumbnail Image para todos os slides de uma apresentação com dimensionamento personalizado.

### Retorna

Bitmap objects.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions) | Rendering options. |
| scale_x | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scale_y | **float** | The value by which to scale this Thumbnail in the y-axis direction. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
Retorna objetos Thumbnail Image para slides especificados de uma apresentação com tamanho especificado.

### Retorna

Bitmap objects.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| image_size | [`Size`](/slides/python-net/pt/aspose.slides/size) | Size of the image to create. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Retorna objetos Thumbnail Image para slides especificados de uma apresentação com dimensionamento personalizado.

### Retorna

Bitmap objects.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| scale_x | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scale_y | **float** | The value by which to scale this Thumbnail in the y-axis direction. |



### Veja Também
* classe [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation)
* classe [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions)
* classe [`Size`](/slides/python-net/pt/aspose.slides/size)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)