---
title: refresh_data method
second_title: Aspose.Slides a Python számára a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/ichartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Frissíti a diagram adatait az eredeti munkafüzetből való újratöltéssel.

```python
def refresh_data(self):
    ...
```

### Megjegyzések

Ha a diagram külső munkafüzetet használ, a munkafüzetnek elérhetőnek kell lennie a hívás időpontjában.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kivétel akkor dobódik, ha a munkafüzet formátuma nem támogatott, vagy ha [`IChartData.data_source_type`](/slides/python-net/hu/aspose.slides.charts/ichartdata/data_source_type)<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/hu/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) és a külső munkafüzet nem érhető el vagy nem tölthető be. |

### Lásd még
* osztály [`IChartData`](/slides/python-net/hu/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)