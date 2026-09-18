---
title: get_or_create_data_point_by_idx method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/chartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
Se a coleção já contém um ponto de dados com o índice `index`, então retorna esse ponto de dados.
Se a coleção não contém um ponto de dados com o índice `index`==N (quando o número de pontos de dados nesta coleção é menor ou igual a N), então adiciona pontos de dados deficientes e retorna o último (que tem o índice solicitado).
Por exemplo, os índices da coleção são {0, 1, 2}, e o índice solicitado é 5. Então o método adiciona pontos de dados deficientes: {0, 1, 2, 3, 4, 5}. E retorna o ponto de dados com índice 5.

### Retorna

Retorna o ponto de dados com o índice solicitado.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | Index. |



### Veja também
* classe [`ChartDataPointCollection`](/slides/python-net/pt/aspose.slides.charts/chartdatapointcollection)
* classe [`IChartDataPoint`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)