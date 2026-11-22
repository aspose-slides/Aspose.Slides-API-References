---
title: refresh_data method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Menyegarkan data diagram dengan memuat ulang dari workbook sumber.


```python
def refresh_data(self):
    ...
```


### Catatan

Jika diagram menggunakan workbook eksternal, workbook harus dapat diakses pada saat pemanggilan.

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Dilemparkan ketika format workbook tidak didukung, atau ketika [`ChartData.data_source_type`](/slides/python-net/id/aspose.slides.charts/chartdata/data_source_type) adalah<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/id/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) dan workbook eksternal tidak dapat diakses atau dimuat. |



### Lihat Juga
* kelas [`ChartData`](/slides/python-net/id/aspose.slides.charts/chartdata)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)