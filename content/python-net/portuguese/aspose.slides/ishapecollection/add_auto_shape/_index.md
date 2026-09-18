---
title: add_auto_shape method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/ishapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Cria uma nova forma automática com formatação padrão e a adiciona ao final da coleção de formas.

### Retorna

O [`IAutoShape`](/slides/python-net/pt/aspose.slides/iautoshape) recém-criado.



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype) | O [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype) da forma automática a ser adicionada. |
| x | **float** | A coordenada x da moldura da forma, em pontos. |
| y | **float** | A coordenada y da moldura da forma, em pontos. |
| width | **float** | A largura da moldura da forma, em pontos. |
| height | **float** | A altura da moldura da forma, em pontos. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Cria uma nova forma automática e a adiciona ao final da coleção de formas, opcionalmente inicializando-a com a formatação de modelo padrão.

### Retorna

O [`IAutoShape`](/slides/python-net/pt/aspose.slides/iautoshape) recém-criado.



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype) | O [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype) da forma automática a ser adicionada. |
| x | **float** | A coordenada x da moldura da forma, em pontos. |
| y | **float** | A coordenada y da moldura da forma, em pontos. |
| width | **float** | A largura da moldura da forma, em pontos. |
| height | **float** | A altura da moldura da forma, em pontos. |
| create_from_template | **bool** | True para aplicar o estilo de modelo padrão (estilo simples, texto centralizado e nome não vazio)<br/><br/>            à nova forma; false para criar a forma com todas as propriedades definidas para seus valores padrão. |



### Ver Também
* classe [`IAutoShape`](/slides/python-net/pt/aspose.slides/iautoshape)
* classe [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection)
* enumeração [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)