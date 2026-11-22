---
title: refresh_data method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Vernieuwt de grafiekgegevens door ze opnieuw te laden vanuit de bronwerkmap.


```python
def refresh_data(self):
    ...
```


### Opmerkingen

Als de grafiek een externe werkmap gebruikt, moet de werkmap toegankelijk zijn op het moment van het aanroepen.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wordt gegooid wanneer het werkmapformaat niet wordt ondersteund, of wanneer [`ChartData.data_source_type`](/slides/python-net/nl/aspose.slides.charts/chartdata/data_source_type) is<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/nl/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) en de externe werkmap niet kan worden benaderd of geladen. |



### Zie ook
* klasse [`ChartData`](/slides/python-net/nl/aspose.slides.charts/chartdata)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)