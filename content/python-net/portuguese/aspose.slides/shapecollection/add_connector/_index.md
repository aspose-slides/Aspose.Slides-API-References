---
title: add_connector method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/shapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Cria uma nova forma de conector com estilo de modelo padrão e a adiciona ao final da coleção de formas.

### Returns

O [`IConnector`](/slides/python-net/pt/aspose.slides/iconnector) recém-criado.



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype) | O [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype) da forma de conector a ser adicionada. |
| x | **float** | A coordenada x da moldura do conector, em pontos. |
| y | **float** | A coordenada y da moldura do conector, em pontos. |
| width | **float** | A largura da moldura do conector, em pontos. |
| height | **float** | A altura da moldura do conector, em pontos. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Cria uma nova forma de conector e a adiciona ao final da coleção de formas, opcionalmente aplicando o estilo de modelo padrão.

### Returns

O [`IConnector`](/slides/python-net/pt/aspose.slides/iconnector) recém-criado.



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype) | O [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype) da forma de conector a ser criada. |
| x | **float** | A coordenada x da moldura do conector, em pontos. |
| y | **float** | A coordenada y da moldura do conector, em pontos. |
| width | **float** | A largura da moldura do conector, em pontos. |
| height | **float** | A altura da moldura do conector, em pontos. |
| create_from_template | **bool** | True para aplicar o estilo de modelo padrão (nome não vazio, estilo simples); <br/><br/>            false para criar o conector com valores de propriedade padrão. |



### Veja Também
* classe [`IConnector`](/slides/python-net/pt/aspose.slides/iconnector)
* classe [`ShapeCollection`](/slides/python-net/pt/aspose.slides/shapecollection)
* enumeração [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)