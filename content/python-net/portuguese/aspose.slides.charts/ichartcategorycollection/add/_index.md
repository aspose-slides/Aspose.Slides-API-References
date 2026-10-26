---
title: add method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/ichartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Se a categoria existir na coleção, retorne-a. Caso contrário, cria uma nova categoria de gráfico a partir de [`IChartDataCell`](/slides/python-net/pt/aspose.slides.charts/ichartdatacell) e a adiciona à coleção.

### Retorno

Categoria adicionada ou existente.



```python
def add(self, chart_data_cell):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/pt/aspose.slides.charts/ichartdatacell) | Célula usada para criar a categoria de gráfico. |


## add(self, value) {#any}
Cria um novo [`IChartCategory`](/slides/python-net/pt/aspose.slides.charts/ichartcategory) a partir do valor e o adiciona à coleção.

### Retorno

Adicionado [`IChartCategory`](/slides/python-net/pt/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| value | **any** | O valor. |

### Observações

Este método adiciona uma planilha com o nome AUTO_DATA e adiciona todos os valores lá.  
Se você usar [`IChartDataWorkbook`](/slides/python-net/pt/aspose.slides.charts/ichartdataworkbook) para adicionar ou editar valores de célula, certifique-se de que não use esta planilha.  
O número máximo de valores adicionados usando este método não deve ultrapassar 16711680

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | se o limite for excedido |



### Ver Também
* classe [`IChartCategory`](/slides/python-net/pt/aspose.slides.charts/ichartcategory)
* classe [`IChartCategoryCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection)
* classe [`IChartDataCell`](/slides/python-net/pt/aspose.slides.charts/ichartdatacell)
* classe [`IChartDataWorkbook`](/slides/python-net/pt/aspose.slides.charts/ichartdataworkbook)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)