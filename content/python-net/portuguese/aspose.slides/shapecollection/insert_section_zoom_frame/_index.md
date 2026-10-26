---
title: insert_section_zoom_frame method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Cria um novo quadro Section Zoom e o insere na coleção de formas no índice especificado.

### Retorno

O novo [`ISectionZoomFrame`](/slides/python-net/pt/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice baseado em zero onde o quadro Section Zoom será inserido. |
| x | **float** | A coordenada x do novo quadro Section Zoom, em pontos. |
| y | **float** | A coordenada y do novo quadro Section Zoom, em pontos. |
| width | **float** | A largura do novo quadro Section Zoom, em pontos. |
| height | **float** | A altura do novo quadro Section Zoom, em pontos. |
| section | [`ISection`](/slides/python-net/pt/aspose.slides/isection) | O [`ISection`](/slides/python-net/pt/aspose.slides/isection) referenciado pelo quadro Section Zoom;<br/><br/>            deve pertencer a esta apresentação e conter ao menos um slide. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançada se a seção referenciada não pertencer à apresentação atual ou não contiver slides. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Cria um novo quadro Section Zoom com uma imagem predefinida e o insere na coleção de formas no índice especificado.

### Retorno

O novo [`ISectionZoomFrame`](/slides/python-net/pt/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice baseado em zero onde o quadro Section Zoom será inserido. |
| x | **float** | A coordenada x do novo quadro Section Zoom, em pontos. |
| y | **float** | A coordenada y do novo quadro Section Zoom, em pontos. |
| width | **float** | A largura do novo quadro Section Zoom, em pontos. |
| height | **float** | A altura do novo quadro Section Zoom, em pontos. |
| section | [`ISection`](/slides/python-net/pt/aspose.slides/isection) | O [`ISection`](/slides/python-net/pt/aspose.slides/isection) referenciado pelo quadro Section Zoom;<br/><br/>            deve pertencer a esta apresentação e conter ao menos um slide. |
| image | [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage) | A imagem a ser exibida dentro do quadro Section Zoom. |

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