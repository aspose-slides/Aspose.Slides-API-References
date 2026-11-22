---
title: refresh_data method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/ichartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Obnoví data grafu načtením z výchozího sešitu.

```python
def refresh_data(self):
    ...
```

### Poznámky

Pokud graf používá externí sešit, musí být sešit přístupný v okamžiku volání.

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Vyvoláno, když formát sešitu není podporován, nebo když [`IChartData.data_source_type`](/slides/python-net/cs/aspose.slides.charts/ichartdata/data_source_type) je<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/cs/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) a externí sešit nelze získat nebo načíst. |

### Viz také
* třída [`IChartData`](/slides/python-net/cs/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)