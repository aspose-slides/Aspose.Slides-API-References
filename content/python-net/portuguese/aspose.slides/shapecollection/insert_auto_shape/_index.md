---
title: insert_auto_shape method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Cria uma nova forma automática e a insere na coleção de formas no índice especificado, aplicando a formatação de modelo padrão.

### Retorno

O [`IAutoShape`](/slides/python-net/pt/aspose.slides/iautoshape) recém-criado.



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice baseado em zero no qual inserir a nova forma automática. |
| shape_type | [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype) | O [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype) da forma automática a inserir. |
| x | **float** | Coordenada x da moldura da forma, em pontos. |
| y | **float** | Coordenada y da moldura da forma, em pontos. |
| width | **float** | Largura da moldura da forma, em pontos. |
| height | **float** | Altura da moldura da forma, em pontos. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Cria uma nova forma automática e a insere na coleção de formas no índice especificado, opcionalmente inicializando-a com o estilo de modelo padrão.

### Retorno

O [`IAutoShape`](/slides/python-net/pt/aspose.slides/iautoshape) recém-criado.



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice baseado em zero no qual inserir a forma automática. |
| shape_type | [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype) | O [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype) da forma automática a inserir. |
| x | **float** | Coordenada x da moldura da forma, em pontos. |
| y | **float** | Coordenada y da moldura da forma, em pontos. |
| width | **float** | Largura da moldura da forma, em pontos. |
| height | **float** | Altura da moldura da forma, em pontos. |
| create_from_template | **bool** | True para aplicar o estilo de modelo padrão (incluindo um nome não vazio, estilo simples e texto centralizado); <br/><br/> false para criar a forma com todas as propriedades definidas para seus valores padrão. |



### Veja Também
* classe [`IAutoShape`](/slides/python-net/pt/aspose.slides/iautoshape)
* classe [`ShapeCollection`](/slides/python-net/pt/aspose.slides/shapecollection)
* enumeração [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)