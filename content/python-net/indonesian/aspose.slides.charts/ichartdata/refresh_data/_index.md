---
title: refresh_data method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/ichartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Menyegarkan data chart dengan memuat ulangnya dari workbook sumber.


```python
def refresh_data(self):
    ...
```


### Catatan

Jika chart menggunakan workbook eksternal, workbook harus dapat diakses pada saat pemanggilan.

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Dilempar ketika format workbook tidak didukung, atau ketika [`IChartData.data_source_type`](/slides/python-net/id/aspose.slides.charts/ichartdata/data_source_type) adalah<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/id/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) dan workbook eksternal tidak dapat diakses atau dimuat. |



### Lihat Juga
* kelas [`IChartData`](/slides/python-net/id/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)