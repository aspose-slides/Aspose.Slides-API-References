---
title: add_section_zoom_frame method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/shapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Cria uma nova moldura de Zoom de Seção e a adiciona ao final da coleção de formas.

### Retorno

O [`ISectionZoomFrame`](/slides/python-net/pt/aspose.slides/isectionzoomframe) recém-criado.



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| x | **float** | A coordenada x da nova moldura de Zoom de Seção, em pontos. |
| y | **float** | A coordenada y da nova moldura de Zoom de Seção, em pontos. |
| width | **float** | A largura da nova moldura de Zoom de Seção, em pontos. |
| height | **float** | A altura da nova moldura de Zoom de Seção, em pontos. |
| section | [`ISection`](/slides/python-net/pt/aspose.slides/isection) | O [`ISection`](/slides/python-net/pt/aspose.slides/isection) referenciado pela moldura de Zoom de Seção; <br/><br/>            deve pertencer a esta apresentação e conter ao menos um slide. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançada se a seção referenciada não pertencer à apresentação atual ou não contiver slides. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Cria uma nova moldura de Zoom de Seção com uma imagem predefinida e a adiciona ao final da coleção de formas.

### Retorno

O [`ISectionZoomFrame`](/slides/python-net/pt/aspose.slides/isectionzoomframe) recém-criado.



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| x | **float** | A coordenada x da nova moldura de Zoom de Seção, em pontos. |
| y | **float** | A coordenada y da nova moldura de Zoom de Seção, em pontos. |
| width | **float** | A largura da nova moldura de Zoom de Seção, em pontos. |
| height | **float** | A altura da nova moldura de Zoom de Seção, em pontos. |
| section | [`ISection`](/slides/python-net/pt/aspose.slides/isection) | O [`ISection`](/slides/python-net/pt/aspose.slides/isection) referenciado pela moldura de Zoom de Seção; <br/><br/>            deve pertencer a esta apresentação e conter ao menos um slide. |
| image | [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage) | O [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage) a ser exibido dentro da moldura de Zoom de Seção. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançada se a seção referenciada não pertencer à apresentação atual ou não contiver slides. |



### Veja Também
* classe [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage)
* classe [`ISection`](/slides/python-net/pt/aspose.slides/isection)
* classe [`ISectionZoomFrame`](/slides/python-net/pt/aspose.slides/isectionzoomframe)
* classe [`ShapeCollection`](/slides/python-net/pt/aspose.slides/shapecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)