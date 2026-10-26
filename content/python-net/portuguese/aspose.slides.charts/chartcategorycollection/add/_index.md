---
title: add method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Se a categoria existir na coleção, retorná-la. Caso contrário, cria uma nova categoria de gráfico a partir de [`IChartDataCell`](/slides/python-net/pt/aspose.slides.charts/ichartdatacell) e a adiciona à coleção.

### Retorna

Categoria adicionada ou existente.



```python
def add(self, chart_data_cell):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/pt/aspose.slides.charts/ichartdatacell) | Célula usada para criar a categoria de gráfico. |


## add(self, value) {#any}
Cria um novo [`ChartCategory`](/slides/python-net/pt/aspose.slides.charts/chartcategory) a partir do valor e o adiciona à coleção.

### Retorna

Adicionado [`IChartCategory`](/slides/python-net/pt/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| value | **any** | O valor. |

### Observações

Este método adiciona uma planilha com o nome AUTO_DATA e adiciona todos os valores nela. Se você usar [`ChartDataWorkbook`](/slides/python-net/pt/aspose.slides.charts/chartdataworkbook) para adicionar ou editar valores de células, certifique-se de que não utilize esta planilha. O número máximo de valores adicionados usando este método não deve exceder 16711680

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | se o limite for excedido |



### Ver Também
* classe [`ChartCategory`](/slides/python-net/pt/aspose.slides.charts/chartcategory)
* classe [`ChartCategoryCollection`](/slides/python-net/pt/aspose.slides.charts/chartcategorycollection)
* classe [`ChartDataWorkbook`](/slides/python-net/pt/aspose.slides.charts/chartdataworkbook)
* classe [`IChartCategory`](/slides/python-net/pt/aspose.slides.charts/ichartcategory)
* classe [`IChartDataCell`](/slides/python-net/pt/aspose.slides.charts/ichartdatacell)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)