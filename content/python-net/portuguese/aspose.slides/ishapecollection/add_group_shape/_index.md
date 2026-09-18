---
title: add_group_shape method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/ishapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Cria um novo shape de grupo vazio e o adiciona ao final da coleção de shapes.
A moldura do grupo será ajustada automaticamente para caber quaisquer shapes adicionados a ele.

### Retorna

O [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape) recém-criado.



```python
def add_group_shape(self):
    ...
```



## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Cria um novo shape de grupo, converte a imagem SVG especificada em shapes individuais,
e adiciona o grupo resultante ao final da coleção de shapes.

### Retorna

O [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape) recém-criado.



```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/pt/aspose.slides/isvgimage) | O [`ISvgImage`](/slides/python-net/pt/aspose.slides/isvgimage) contendo conteúdo vetorial para converter em shapes. |
| x | **float** | A coordenada x da moldura do grupo, em pontos. |
| y | **float** | A coordenada y da moldura do grupo, em pontos. |
| width | **float** | A largura da moldura do grupo, em pontos. |
| height | **float** | A altura da moldura do grupo, em pontos. |



### Ver também
* classe [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape)
* classe [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection)
* classe [`ISvgImage`](/slides/python-net/pt/aspose.slides/isvgimage)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)