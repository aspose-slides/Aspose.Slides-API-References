---
title: refresh_data method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Atualiza os dados do gráfico recarregando-os da pasta de trabalho origem.


```python
def refresh_data(self):
    ...
```


### Observações

Se o gráfico usa uma pasta de trabalho externa, a pasta de trabalho deve estar acessível no momento da chamada.

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lançada quando o formato da pasta de trabalho não é suportado, ou quando [`ChartData.data_source_type`](/slides/python-net/pt/aspose.slides.charts/chartdata/data_source_type) está<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/pt/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) e a pasta de trabalho externa não pode ser acessada ou carregada. |



### Ver também
* classe [`ChartData`](/slides/python-net/pt/aspose.slides.charts/chartdata)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)