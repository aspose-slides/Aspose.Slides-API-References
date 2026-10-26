---
title: add method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
Adiciona nova célula à coleção.

```python
def add(self, cell):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/pt/aspose.slides.charts/ichartdatacell) | Nova célula a ser adicionada. |

## add(self, value) {#any}
Cria [`ChartDataCell`](/slides/python-net/pt/aspose.slides.charts/chartdatacell) a partir do valor especificado e o adiciona à coleção.

```python
def add(self, value):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| value | **any** | O valor. |

### Observações

Este método adiciona uma planilha com o nome AUTO_DATA e adiciona todos os valores lá.  Se você usar [`ChartDataWorkbook`](/slides/python-net/pt/aspose.slides.charts/chartdataworkbook) para adicionar ou editar valores de Cell, certifique-se de que não use esta planilha
            O número máximo de valores adicionados usando este método não deve exceder 16711680

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | se o limite for excedido |

### Ver também
* classe [`ChartCellCollection`](/slides/python-net/pt/aspose.slides.charts/chartcellcollection)
* classe [`ChartDataCell`](/slides/python-net/pt/aspose.slides.charts/chartdatacell)
* classe [`ChartDataWorkbook`](/slides/python-net/pt/aspose.slides.charts/chartdataworkbook)
* classe [`IChartDataCell`](/slides/python-net/pt/aspose.slides.charts/ichartdatacell)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)