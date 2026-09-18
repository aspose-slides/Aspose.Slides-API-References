---
title: add_chart method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/ishapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
Cria um novo gráfico, inicializa-o com dados e configurações de série de amostra e adiciona
            ele ao final da coleção de formas.

### Retorna

O [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart) recém-criado.



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/pt/aspose.slides.charts/charttype) | O tipo de gráfico a ser adicionado. |
| x | **float** | A coordenada x do novo gráfico, em pontos. |
| y | **float** | A coordenada y do novo gráfico, em pontos. |
| width | **float** | A largura do gráfico, em pontos. |
| height | **float** | A altura do gráfico, em pontos. |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
Cria um novo gráfico, inicializa-o com dados e configurações de série de amostra e adiciona
            ele ao final da coleção de formas.

### Retorna

O [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart) recém-criado.



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/pt/aspose.slides.charts/charttype) | O tipo de gráfico a ser adicionado. |
| x | **float** | A coordenada x do novo gráfico, em pontos. |
| y | **float** | A coordenada y do novo gráfico, em pontos. |
| width | **float** | A largura do gráfico, em pontos. |
| height | **float** | A altura do gráfico, em pontos. |
| init_with_sample | **bool** | True para inicializar o novo gráfico com dados e configurações de série de amostra; <br/><br/>            false para criar o gráfico sem séries e somente com configurações mínimas, o que torna a criação mais rápida. |



### Ver Também
* enumeração [`ChartType`](/slides/python-net/pt/aspose.slides.charts/charttype)
* classe [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart)
* classe [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)