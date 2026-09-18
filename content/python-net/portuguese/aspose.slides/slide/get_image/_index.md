---
title: get_image method
second_title: Aspose.Slides para Python via .NET Referência da API
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



## get_image(self, image_size) {#asposepydrawingsize}
Retorna um objeto Thumbnail Image com tamanho especificado.

### Retorna

Objeto Image.

```python
def get_image(self, image_size):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | Tamanho da imagem a ser criada. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Retorna um objeto Thumbnail tiff image com parâmetros especificados.

### Retorna

Objeto Image.

```python
def get_image(self, options):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/pt/aspose.slides.export/itiffoptions) | Opções tiff. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lançada quando options.SlideLayoutOption é NotesCommentsLayoutingOptions e sua propriedade NotesPosition tem o valor NotesPositions.BottomFull. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Retorna um objeto Thumbnail Image.

### Retorna

Objeto Image.

```python
def get_image(self, options):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions) | Opções de renderização. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lançada quando notesCommentsLayouting.NotesPosition tem o valor NotesPositions.BottomFull. |


## get_image(self, scale_x, scale_y) {#float-float}
Retorna um objeto Thumbnail Image com dimensionamento personalizado.

### Retorna

Objeto IImage.

```python
def get_image(self, scale_x, scale_y):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| scale_x | **float** | O valor pelo qual dimensionar este Thumbnail no eixo x. |
| scale_y | **float** | O valor pelo qual dimensionar este Thumbnail no eixo y. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Retorna um objeto Thumbnail Image com tamanho especificado.

### Retorna

Objeto Image.

```python
def get_image(self, options, image_size):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions) | Opções de renderização. |
| image_size | **aspose.slides.Size** | Tamanho da imagem a ser criada. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lançada quando options.SlideLayoutOption é NotesCommentsLayoutingOptions e sua propriedade NotesPosition tem o valor NotesPositions.BottomFull. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Retorna um objeto Thumbnail Image com dimensionamento personalizado.

### Retorna

Objetos Bitmap.

```python
def get_image(self, options, scale_x, scale_y):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions) | Opções de renderização. |
| scale_x | **float** | O valor pelo qual dimensionar este Thumbnail no eixo x. |
| scale_y | **float** | O valor pelo qual dimensionar este Thumbnail no eixo y. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lançada quando notesCommentsLayouting.NotesPosition tem o valor NotesPositions.BottomFull. |



### Veja Também
* classe [`IImage`](/slides/python-net/pt/aspose.slides/iimage)
* classe [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions)
* classe [`ITiffOptions`](/slides/python-net/pt/aspose.slides.export/itiffoptions)
* classe [`Slide`](/slides/python-net/pt/aspose.slides/slide)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)