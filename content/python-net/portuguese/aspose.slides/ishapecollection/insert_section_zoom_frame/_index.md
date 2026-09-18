---
title: insert_section_zoom_frame method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/ishapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Cria um novo Section Zoom frame e o insere na coleção de formas no índice especificado.

### Retorno

O [`ISectionZoomFrame`](/slides/python-net/pt/aspose.slides/isectionzoomframe) recém-criado.



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | O índice baseado em zero no qual inserir o Section Zoom frame. |
| x | **float** | A coordenada x do novo Section Zoom frame, em pontos. |
| y | **float** | A coordenada y do novo Section Zoom frame, em pontos. |
| width | **float** | A largura do novo Section Zoom frame, em pontos. |
| height | **float** | A altura do novo Section Zoom frame, em pontos. |
| section | [`ISection`](/slides/python-net/pt/aspose.slides/isection) | A [`ISection`](/slides/python-net/pt/aspose.slides/isection) referenciada pelo Section Zoom frame;<br/><br/>            deve pertencer a esta apresentação e conter ao menos um slide. |

### Exceções

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançada se a seção referenciada não pertencer à apresentação atual ou não contiver slides. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Cria um novo Section Zoom frame com uma imagem pré-definida e o insere na coleção de formas no índice especificado.

### Retorno

O [`ISectionZoomFrame`](/slides/python-net/pt/aspose.slides/isectionzoomframe) recém-criado.



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | O índice baseado em zero no qual inserir o Section Zoom frame. |
| x | **float** | A coordenada x do novo Section Zoom frame, em pontos. |
| y | **float** | A coordenada y do novo Section Zoom frame, em pontos. |
| width | **float** | A largura do novo Section Zoom frame, em pontos. |
| height | **float** | A altura do novo Section Zoom frame, em pontos. |
| section | [`ISection`](/slides/python-net/pt/aspose.slides/isection) | A [`ISection`](/slides/python-net/pt/aspose.slides/isection) referenciada pelo Section Zoom frame;<br/><br/>            deve pertencer a esta apresentação e conter ao menos um slide. |
| image | [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage) | A imagem a ser exibida dentro do Section Zoom frame. |

### Exceções

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançada se a seção referenciada não pertencer à apresentação atual ou não contiver slides. |



### Ver também
* classe [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage)
* classe [`ISection`](/slides/python-net/pt/aspose.slides/isection)
* classe [`ISectionZoomFrame`](/slides/python-net/pt/aspose.slides/isectionzoomframe)
* classe [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)