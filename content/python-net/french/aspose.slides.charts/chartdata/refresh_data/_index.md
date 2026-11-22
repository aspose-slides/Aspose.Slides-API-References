---
title: refresh_data method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Rafraîchit les données du graphique en les rechargeant depuis le classeur source.

```python
def refresh_data(self):
    ...
```

### Remarques

Si le graphique utilise un classeur externe, le classeur doit être accessible au moment de l'appel.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lancé lorsque le format du classeur n'est pas pris en charge, ou lorsque [`ChartData.data_source_type`](/slides/python-net/fr/aspose.slides.charts/chartdata/data_source_type) est<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/fr/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) et que le classeur externe ne peut pas être accédé ou chargé. |

### Voir aussi
* classe [`ChartData`](/slides/python-net/fr/aspose.slides.charts/chartdata)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)