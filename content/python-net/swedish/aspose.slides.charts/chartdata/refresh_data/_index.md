---
title: refresh_data method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Uppdaterar diagramdata genom att läsa in den från källarboken.


```python
def refresh_data(self):
    ...
```


### Anmärkningar

Om diagrammet använder en extern arbetsbok måste arbetsboken vara åtkomlig när metoden anropas.

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kastas när arbetsboksformatet inte stöds, eller när [`ChartData.data_source_type`](/slides/python-net/sv/aspose.slides.charts/chartdata/data_source_type) är<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/sv/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) och den externa arbetsboken inte kan nås eller läsas in. |


### Se även
* klass [`ChartData`](/slides/python-net/sv/aspose.slides.charts/chartdata)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)