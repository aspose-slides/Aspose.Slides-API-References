---
title: set_external_workbook method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
Mengatur workbook eksternal sebagai sumber data untuk diagram. Data diagram akan diperbarui dari workbook target.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| workbook_path | **str** | Jalur ke workbook target |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Workbook eksternal tidak tersedia atau tidak dapat dimuat. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Mengatur workbook eksternal sebagai sumber data untuk diagram.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| workbook_path | **str** | Jalur ke workbook target |
| update_chart_data | **bool** | Jika nilai false hanya jalur workbook yang akan diperbarui. <br/><br/>             Data diagram tidak akan dimuat dan diperbarui dari workbook target. Dapat digunakan ketika workbook target tidak ada atau tidak tersedia.<br/><br/>             Jika nilai true data diagram akan diperbarui dari workbook target. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Workbook eksternal tidak tersedia atau tidak dapat dimuat. |



### Lihat Juga
* kelas [`IChartData`](/slides/python-net/id/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)