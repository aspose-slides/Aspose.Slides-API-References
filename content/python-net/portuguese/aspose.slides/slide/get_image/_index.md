---
title: get_image method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Retorna um objeto Thumbnail Image (20% do tamanho real).


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
Retorna um objeto Thumbnail Image com o tamanho especificado.

### Returns

Objeto Image.



```python
def get_image(self, image_size):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/pt/aspose.slides/size) | Tamanho da imagem a ser criada. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Retorna um objeto de imagem tiff Thumbnail com os parâmetros especificados.

### Returns

Objeto Image.



```python
def get_image(self, options):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/pt/aspose.slides.export/itiffoptions) | Opções tiff. |

### Exceptions

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lançada quando options.SlideLayoutOption é NotesCommentsLayoutingOptions e sua propriedade NotesPosition recebe o valor NotesPositions.BottomFull. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Retorna um objeto Thumbnail Image.

### Returns

Objeto Image.



```python
def get_image(self, options):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions) | Opções de renderização. |

### Exceptions

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lançada quando notesCommentsLayouting.NotesPosition recebe o valor NotesPositions.BottomFull. |


## get_image(self, scale_x, scale_y) {#float-float}
Retorna um objeto Thumbnail Image com dimensionamento personalizado.

### Returns

Objeto IImage.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| scale_x | **float** | O valor pelo qual dimensionar este Thumbnail na direção do eixo x. |
| scale_y | **float** | O valor pelo qual dimensionar este Thumbnail na direção do eixo y. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Retorna um objeto Thumbnail Image com o tamanho especificado.

### Returns

Objeto Image.



```python
def get_image(self, options, image_size):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions) | Opções de renderização. |
| image_size | [`Size`](/slides/python-net/pt/aspose.slides/size) | Tamanho da imagem a ser criada. |

### Exceptions

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lançada quando options.SlideLayoutOption é NotesCommentsLayoutingOptions e sua propriedade NotesPosition recebe o valor NotesPositions.BottomFull. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Retorna um objeto Thumbnail Image com dimensionamento personalizado.

### Returns

Objetos Bitmap.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions) | Opções de renderização. |
| scale_x | **float** | O valor pelo qual dimensionar este Thumbnail na direção do eixo x. |
| scale_y | **float** | O valor pelo qual dimensionar este Thumbnail na direção do eixo y. |

### Exceptions

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lançada quando notesCommentsLayouting.NotesPosition recebe o valor NotesPositions.BottomFull. |



### Veja Também
* classe [`IImage`](/slides/python-net/pt/aspose.slides/iimage)
* classe [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions)
* classe [`ITiffOptions`](/slides/python-net/pt/aspose.slides.export/itiffoptions)
* classe [`Slide`](/slides/python-net/pt/aspose.slides/slide)
* classe [`Size`](/slides/python-net/pt/aspose.slides/size)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)