---
title: set_external_workbook method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/chartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
Mengatur workbook eksternal sebagai sumber data untuk diagram. Data diagram akan diperbarui dari workbook target.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| workbook_path | **str** | Path ke workbook target |

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
| workbook_path | **str** | Path ke workbook target |
| update_chart_data | **bool** | Jika nilai false, hanya path workbook yang akan diperbarui. <br/><br/>             Data diagram tidak akan dimuat dan diperbarui dari workbook target. Dapat digunakan ketika workbook target tidak ada atau tidak tersedia.<br/><br/>             Jika nilai true, data diagram akan diperbarui dari workbook target. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Workbook eksternal tidak tersedia atau tidak dapat dimuat. |



### Lihat Juga
* kelas [`ChartData`](/slides/python-net/id/aspose.slides.charts/chartdata)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)