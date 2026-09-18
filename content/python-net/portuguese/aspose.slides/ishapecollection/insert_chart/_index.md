---
title: insert_chart method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/ishapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Cria um novo gráfico, inicializa-o com dados e configurações de série de exemplo e o insere na coleção de formas no índice especificado.

### Retorna

O [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart) recém-criado.



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/pt/aspose.slides.charts/charttype) | O tipo de gráfico a ser criado. |
| x | **float** | A coordenada x do novo gráfico, em pontos. |
| y | **float** | A coordenada y do novo gráfico, em pontos. |
| width | **float** | A largura do novo gráfico, em pontos. |
| height | **float** | A altura do novo gráfico, em pontos. |
| index | **int** | O índice baseado em zero no qual inserir o novo gráfico na coleção de formas. |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Cria um novo gráfico, inicializa-o com dados e configurações de série de exemplo e o insere na coleção de formas no índice especificado.

### Retorna

O [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart) recém-criado.



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/pt/aspose.slides.charts/charttype) | O tipo de gráfico a ser criado. |
| x | **float** | A coordenada x do novo gráfico, em pontos. |
| y | **float** | A coordenada y do novo gráfico, em pontos. |
| width | **float** | A largura do novo gráfico, em pontos. |
| height | **float** | A altura do novo gráfico, em pontos. |
| index | **int** | O índice baseado em zero no qual inserir o novo gráfico na coleção de formas. |
| init_with_sample | **bool** | True para inicializar o novo gráfico com dados e configurações de série de exemplo;<br/><br/>false para criar o gráfico sem séries e apenas com configurações mínimas, o que torna a criação mais rápida. |



### Veja Também
* enumeração [`ChartType`](/slides/python-net/pt/aspose.slides.charts/charttype)
* classe [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart)
* classe [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)