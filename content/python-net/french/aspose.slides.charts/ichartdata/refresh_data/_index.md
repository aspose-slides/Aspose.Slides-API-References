---
title: refresh_data method
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides.charts/ichartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Actualise les données du graphique en les rechargeant depuis le classeur source.


```python
def refresh_data(self):
    ...
```


### Remarques

Si le graphique utilise un classeur externe, le classeur doit être accessible au moment de l’appel.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lancée lorsque le format du classeur n’est pas pris en charge, ou lorsque [`IChartData.data_source_type`](/slides/python-net/fr/aspose.slides.charts/ichartdata/data_source_type) est<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/fr/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) et que le classeur externe ne peut pas être accédé ou chargé. |



### Voir aussi
* classe [`IChartData`](/slides/python-net/fr/aspose.slides.charts/ichartdata)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)