---
title: get_images method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Retorna objetos de imagem em miniatura para todos os slides de uma apresentação.

### Retorna

Objetos Bitmap.



```python
def get_images(self, options):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions) | Opções de renderização. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Retorna objetos Bitmap em miniatura para os slides especificados de uma apresentação.

### Retorna

Objetos Bitmap.



```python
def get_images(self, options, slides):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions) | Opções de renderização. |
| slides | **List[int]** | Array com posições de slides, começando em 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Retorna objetos de imagem em miniatura para todos os slides de uma apresentação com o tamanho especificado.

### Retorna

Objetos Bitmap.



```python
def get_images(self, options, image_size):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions) | Opções de renderização. |
| image_size | **aspose.slides.Size** | Tamanho da imagem a ser criada. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Retorna objetos de imagem em miniatura para todos os slides de uma apresentação com dimensionamento personalizado.

### Retorna

Objetos Bitmap.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions) | Opções de renderização. |
| scale_x | **float** | O valor pelo qual escalar esta miniatura na direção do eixo x. |
| scale_y | **float** | O valor pelo qual escalar esta miniatura na direção do eixo y. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Retorna objetos de imagem em miniatura para os slides especificados de uma apresentação com o tamanho especificado.

### Retorna

Objetos Bitmap.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions) | Opções de renderização. |
| slides | **List[int]** | Array com posições de slides, começando em 1. |
| image_size | **aspose.slides.Size** | Tamanho da imagem a ser criada. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Retorna objetos de imagem em miniatura para os slides especificados de uma apresentação com dimensionamento personalizado.

### Retorna

Objetos Bitmap.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions) | Opções de renderização. |
| slides | **List[int]** | Array com posições de slides, começando em 1. |
| scale_x | **float** | O valor pelo qual escalar esta miniatura na direção do eixo x. |
| scale_y | **float** | O valor pelo qual escalar esta miniatura na direção do eixo y. |



### Veja também
* classe [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation)
* classe [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)