---
title: add method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Adicionar nova célula à coleção.


```python
def add(self, chart_data_cell):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/pt/aspose.slides.charts/ichartdatacell) | Nova célula a ser adicionada. |


## add(self, value) {#any}
Cria [`IChartDataCell`](/slides/python-net/pt/aspose.slides.charts/ichartdatacell) a partir do valor especificado e o adiciona à coleção.


```python
def add(self, value):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| value | **any** | O valor. |

### Observações

Este método adiciona a planilha com o nome AUTO_DATA e adiciona todos os valores lá. Se você usar [`IChartDataWorkbook`](/slides/python-net/pt/aspose.slides.charts/ichartdataworkbook) para adicionar ou editar valores da célula, certifique-se de não usar esta planilha
            O número máximo de valores adicionados usando este método não deve exceder 16711680

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | se o limite for excedido |



### Veja Também
* classe [`IChartCellCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcellcollection)
* classe [`IChartDataCell`](/slides/python-net/pt/aspose.slides.charts/ichartdatacell)
* classe [`IChartDataWorkbook`](/slides/python-net/pt/aspose.slides.charts/ichartdataworkbook)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)