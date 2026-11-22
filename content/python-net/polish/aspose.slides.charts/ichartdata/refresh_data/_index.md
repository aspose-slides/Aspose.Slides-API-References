---
title: refresh_data method
second_title: Aspose.Slides dla Pythona poprzez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides.charts/ichartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Odświeża dane wykresu, ładując je ponownie z skoroszytu źródłowego.


```python
def refresh_data(self):
    ...
```


### Uwagi

Jeśli wykres używa zewnętrznego skoroszytu, skoroszyt musi być dostępny w momencie wywołania.

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Rzucany, gdy format skoroszytu nie jest obsługiwany, lub gdy [`IChartData.data_source_type`](/slides/python-net/pl/aspose.slides.charts/ichartdata/data_source_type) jest<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/pl/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) i nie można uzyskać dostępu do zewnętrznego skoroszytu lub go załadować. |



### Zobacz także
* klasa [`IChartData`](/slides/python-net/pl/aspose.slides.charts/ichartdata)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)