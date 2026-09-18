---
title: add_chart method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/shapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
Cria um novo chart, inicializa-o com dados de série de exemplo e configurações, e o adiciona ao final da shape collection.

### Retorna

O [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart) recém-criado.



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/pt/aspose.slides.charts/charttype) | O tipo de chart a ser adicionado. |
| x | **float** | A coordenada x do novo chart, em pontos. |
| y | **float** | A coordenada y do novo chart, em pontos. |
| width | **float** | A largura do chart, em pontos. |
| height | **float** | A altura do chart, em pontos. |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
Cria um novo chart, inicializa-o com dados de série de exemplo e configurações, e o adiciona ao final da shape collection.

### Retorna

O [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart) recém-criado.



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/pt/aspose.slides.charts/charttype) | O tipo de chart a ser adicionado. |
| x | **float** | A coordenada x do novo chart, em pontos. |
| y | **float** | A coordenada y do novo chart, em pontos. |
| width | **float** | A largura do chart, em pontos. |
| height | **float** | A altura do chart, em pontos. |
| init_with_sample | **bool** | True para inicializar o novo chart com dados de série de exemplo e configurações; <br/><br/> false para criar o chart sem séries e apenas com configurações mínimas, o que torna a criação <br/><br/> mais rápida. |



### Veja Também
* enumeração [`ChartType`](/slides/python-net/pt/aspose.slides.charts/charttype)
* classe [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart)
* classe [`ShapeCollection`](/slides/python-net/pt/aspose.slides/shapecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)