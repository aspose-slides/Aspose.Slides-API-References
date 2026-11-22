---
title: refresh_data method
second_title: Aspose.Slides dla Pythona via .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Odświeża dane wykresu, ponownie ładując je ze źródłowego skoroszytu.

```python
def refresh_data(self):
    ...
```

### Uwagi

Jeśli wykres używa zewnętrznego skoroszytu, skoroszyt musi być dostępny w momencie wywołania.

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Rzucany, gdy format skoroszytu nie jest obsługiwany, lub gdy [`ChartData.data_source_type`](/slides/python-net/pl/aspose.slides.charts/chartdata/data_source_type) jest<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/pl/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) i nie można uzyskać dostępu do zewnętrznego skoroszytu lub go załadować. |

### Zobacz także
* klasa [`ChartData`](/slides/python-net/pl/aspose.slides.charts/chartdata)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)