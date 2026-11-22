---
title: refresh_data method
second_title: Aspose.Slides Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Frissíti a diagram adatait, újratöltve azokat a forrás munkafüzetből.


```python
def refresh_data(self):
    ...
```


### Megjegyzés

Ha a diagram külső munkafüzetet használ, akkor a munkafüzettel a hívás időpontjában hozzáférhetőnek kell lennie.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kivétel akkor dobódik, amikor a munkafüzet formátuma nem támogatott, vagy amikor [`ChartData.data_source_type`](/slides/python-net/hu/aspose.slides.charts/chartdata/data_source_type) van<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/hu/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) és a külső munkafüzet nem érhető el vagy nem tölthető be. |



### Lásd még
* osztály [`ChartData`](/slides/python-net/hu/aspose.slides.charts/chartdata)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)