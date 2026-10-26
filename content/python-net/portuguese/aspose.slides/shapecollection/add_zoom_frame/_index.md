---
title: add_zoom_frame method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/shapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Cria um novo quadro de Zoom e o adiciona ao final da coleção de formas.

### Retorna

O [`IZoomFrame`](/slides/python-net/pt/aspose.slides/izoomframe) recém-criado.



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| x | **float** | A coordenada x do novo quadro de Zoom, em pontos. |
| y | **float** | A coordenada y do novo quadro de Zoom, em pontos. |
| width | **float** | A largura do novo quadro de Zoom, em pontos. |
| height | **float** | A altura do novo quadro de Zoom, em pontos. |
| slide | [`ISlide`](/slides/python-net/pt/aspose.slides/islide) | O [`ISlide`](/slides/python-net/pt/aspose.slides/islide) referenciado pelo quadro de Zoom; deve pertencer a esta apresentação. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançada se o slide referenciado não pertencer à apresentação atual. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Cria um novo quadro de Zoom e o adiciona ao final da coleção de formas.

### Retorna

O [`IZoomFrame`](/slides/python-net/pt/aspose.slides/izoomframe) recém-criado.



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| x | **float** | A coordenada x do novo quadro de Zoom, em pontos. |
| y | **float** | A coordenada y do novo quadro de Zoom, em pontos. |
| width | **float** | A largura do novo quadro de Zoom, em pontos. |
| height | **float** | A altura do novo quadro de Zoom, em pontos. |
| slide | [`ISlide`](/slides/python-net/pt/aspose.slides/islide) | O [`ISlide`](/slides/python-net/pt/aspose.slides/islide) referenciado pelo quadro de Zoom; deve pertencer a esta apresentação. |
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