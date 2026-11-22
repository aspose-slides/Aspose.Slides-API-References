---
title: refresh_data method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Obnoví data grafu načtením z původního sešitu.

```python
def refresh_data(self):
    ...
```

### Poznámky

Pokud graf používá externí sešit, musí být sešit přístupný v okamžiku volání.

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Vyvoláno, když formát sešitu není podporován, nebo když [`ChartData.data_source_type`](/slides/python-net/cs/aspose.slides.charts/chartdata/data_source_type) je<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/cs/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) a externí sešit nelze získat nebo načíst. |

### Viz také
* třída [`ChartData`](/slides/python-net/cs/aspose.slides.charts/chartdata)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)