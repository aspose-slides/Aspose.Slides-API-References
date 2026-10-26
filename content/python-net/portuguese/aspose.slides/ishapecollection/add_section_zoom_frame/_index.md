---
title: add_section_zoom_frame method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Cria um novo quadro Section Zoom e o adiciona ao final da coleção de formas.

### Retorna

O [`ISectionZoomFrame`](/slides/python-net/pt/aspose.slides/isectionzoomframe) recém-criado.



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| x | **float** | A coordenada x do novo quadro Section Zoom, em pontos. |
| y | **float** | A coordenada y do novo quadro Section Zoom, em pontos. |
| width | **float** | A largura do novo quadro Section Zoom, em pontos. |
| height | **float** | A altura do novo quadro Section Zoom, em pontos. |
| section | [`ISection`](/slides/python-net/pt/aspose.slides/isection) | O [`ISection`](/slides/python-net/pt/aspose.slides/isection) referenciado pelo quadro Section Zoom; <br/><br/>            deve pertencer a esta apresentação e conter ao menos um slide. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançada se a seção referenciada não pertencer à apresentação atual ou não contiver slides. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Cria um novo quadro Section Zoom com uma imagem predefinida e o adiciona ao final da coleção de formas.

### Retorna

O [`ISectionZoomFrame`](/slides/python-net/pt/aspose.slides/isectionzoomframe) recém-criado.



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| x | **float** | A coordenada x do novo quadro Section Zoom, em pontos. |
| y | **float** | A coordenada y do novo quadro Section Zoom, em pontos. |
| width | **float** | A largura do novo quadro Section Zoom, em pontos. |
| height | **float** | A altura do novo quadro Section Zoom, em pontos. |
| section | [`ISection`](/slides/python-net/pt/aspose.slides/isection) | O [`ISection`](/slides/python-net/pt/aspose.slides/isection) referenciado pelo quadro Section Zoom; <br/><br/>            deve pertencer a esta apresentação e conter ao menos um slide. |
| image | [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage) | O [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage) a ser exibido dentro do quadro Section Zoom. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançada se a seção referenciada não pertencer à apresentação atual ou não contiver slides. |



### Veja Também
* classe [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage)
* classe [`ISection`](/slides/python-net/pt/aspose.slides/isection)
* classe [`ISectionZoomFrame`](/slides/python-net/pt/aspose.slides/isectionzoomframe)
* classe [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)