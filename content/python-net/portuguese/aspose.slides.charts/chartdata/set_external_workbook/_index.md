---
title: set_external_workbook method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/chartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
Define a pasta de trabalho externa como fonte de dados para o gráfico. Os dados do gráfico serão atualizados a partir da pasta de trabalho de destino.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| workbook_path | **str** | Caminho para a pasta de trabalho de destino |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | A pasta de trabalho externa não está disponível ou não pode ser carregada. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Define a pasta de trabalho externa como fonte de dados para o gráfico.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| workbook_path | **str** | Caminho para a pasta de trabalho de destino |
| update_chart_data | **bool** | Se o valor for falso, somente o caminho da pasta de trabalho será atualizado. <br/><br/>             Os dados do gráfico não serão carregados nem atualizados a partir da pasta de trabalho de destino. Pode ser usado quando a pasta de trabalho de destino não existe ou não está disponível.<br/><br/>             Se o valor for verdadeiro, os dados do gráfico serão atualizados a partir da pasta de trabalho de destino. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | A pasta de trabalho externa não está disponível ou não pode ser carregada. |



### Veja Também
* classe [`ChartData`](/slides/python-net/pt/aspose.slides.charts/chartdata)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)