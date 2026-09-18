---
title: add_group_shape method
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/shapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Cria uma nova forma de grupo vazia e a adiciona ao final da coleção de formas.
A moldura do grupo será ajustada automaticamente para caber quaisquer formas adicionadas a ele.

### Retorna

O [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape) recém-criado.



```python
def add_group_shape(self):
    ...
```



## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Cria uma nova forma de grupo, converte a imagem SVG especificada em formas individuais e adiciona o grupo resultante ao final da coleção de formas.

### Retorna

O [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape) recém-criado.



```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/pt/aspose.slides/isvgimage) | O [`ISvgImage`](/slides/python-net/pt/aspose.slides/isvgimage) contendo conteúdo vetorial para converter em formas. |
| x | **float** | A coordenada x da moldura do grupo, em pontos. |
| y | **float** | A coordenada y da moldura do grupo, em pontos. |
| width | **float** | A largura da moldura do grupo, em pontos. |
| height | **float** | A altura da moldura do grupo, em pontos. |



### Ver Também
* classe [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape)
* classe [`ISvgImage`](/slides/python-net/pt/aspose.slides/isvgimage)
* classe [`ShapeCollection`](/slides/python-net/pt/aspose.slides/shapecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)