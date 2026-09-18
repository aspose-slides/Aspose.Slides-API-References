---
title: insert_connector method
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/ishapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Cria uma nova forma de conector e a insere na coleção de formas no índice especificado,
            aplicando o estilo de modelo padrão.

### Retorna

A [`IConnector`](/slides/python-net/pt/aspose.slides/iconnector) recém-criada.



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice baseado em zero no qual inserir a forma de conector. |
| shape_type | [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype) | O [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype) da forma de conector a ser inserida. |
| x | **float** | A coordenada x da moldura do conector, em pontos. |
| y | **float** | A coordenada y da moldura do conector, em pontos. |
| width | **float** | A largura da moldura do conector, em pontos. |
| height | **float** | A altura da moldura do conector, em pontos. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Cria uma nova forma de conector e a insere na coleção de formas no índice especificado,
            aplicando opcionalmente o estilo de modelo padrão.

### Retorna

A [`IConnector`](/slides/python-net/pt/aspose.slides/iconnector) recém-criada.



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice baseado em zero no qual inserir a forma de conector. |
| shape_type | [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype) | O [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype) da forma de conector a ser inserida. |
| x | **float** | A coordenada x da moldura do conector, em pontos. |
| y | **float** | A coordenada y da moldura do conector, em pontos. |
| width | **float** | A largura da moldura do conector, em pontos. |
| height | **float** | A altura da moldura do conector, em pontos. |
| create_from_template | **bool** | True para aplicar o estilo de modelo padrão (nome não vazio, estilo simples);<br/><br/>            false para criar o conector com valores de propriedade padrão. |



### Veja Também
* classe [`IConnector`](/slides/python-net/pt/aspose.slides/iconnector)
* classe [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection)
* enumeração [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)