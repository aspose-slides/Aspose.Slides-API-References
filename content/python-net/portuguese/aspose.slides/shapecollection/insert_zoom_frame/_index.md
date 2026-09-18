---
title: insert_zoom_frame method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/shapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Cria um novo Zoom frame e o insere na coleção de shapes no índice especificado.

### Retorna

O [`IZoomFrame`](/slides/python-net/pt/aspose.slides/izoomframe) recém-criado.



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice baseado em zero no qual inserir o Zoom frame. |
| x | **float** | A coordenada x do novo Zoom frame, em pontos. |
| y | **float** | A coordenada y do novo Zoom frame, em pontos. |
| width | **float** | A largura do novo Zoom frame, em pontos. |
| height | **float** | A altura do novo Zoom frame, em pontos. |
| slide | [`ISlide`](/slides/python-net/pt/aspose.slides/islide) | O [`ISlide`](/slides/python-net/pt/aspose.slides/islide) referenciado pelo Zoom frame. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançada se o slide referenciado não pertencer à apresentação atual. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Cria um novo Zoom frame com uma imagem predefinida e o insere na coleção de shapes no índice especificado.

### Retorna

O [`IZoomFrame`](/slides/python-net/pt/aspose.slides/izoomframe) recém-criado.



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice baseado em zero no qual inserir o Zoom frame. |
| x | **float** | A coordenada x do novo Zoom frame, em pontos. |
| y | **float** | A coordenada y do novo Zoom frame, em pontos. |
| width | **float** | A largura do novo Zoom frame, em pontos. |
| height | **float** | A altura do novo Zoom frame, em pontos. |
| slide | [`ISlide`](/slides/python-net/pt/aspose.slides/islide) | O [`ISlide`](/slides/python-net/pt/aspose.slides/islide) referenciado pelo Zoom frame. |
| image | [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage) | A imagem para o slide referenciado [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage). |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançada se o slide referenciado não pertencer à apresentação atual. |



### Veja Também
* classe [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage)
* classe [`ISlide`](/slides/python-net/pt/aspose.slides/islide)
* classe [`IZoomFrame`](/slides/python-net/pt/aspose.slides/izoomframe)
* classe [`ShapeCollection`](/slides/python-net/pt/aspose.slides/shapecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)