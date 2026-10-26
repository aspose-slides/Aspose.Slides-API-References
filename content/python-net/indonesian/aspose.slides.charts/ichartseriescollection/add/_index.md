---
title: add method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/ichartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Membuat seri grafik baru dan menambahkannya ke koleksi.

### Mengembalikan

Seri grafik baru.



```python
def add(self, type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype) | Tipe seri |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Membuat seri grafik baru dari [`IChartDataCell`](/slides/python-net/id/aspose.slides.charts/ichartdatacell) dan menambahkannya ke koleksi.

### Mengembalikan

Seri grafik yang ditambahkan atau seri yang sudah ada di koleksi.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/id/aspose.slides.charts/ichartdatacell) | Sel yang berisi nama seri. |
| type | [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype) | Tipe yang menentukan tipe seri |

### Catatan

Jika seri grafik dibuat dari sel yang sama sudah ada di koleksi, maka metode tidak menambahkan apa-apa dan mengembalikan indeksnya.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Membuat seri grafik baru dari [`IChartCellCollection`](/slides/python-net/id/aspose.slides.charts/ichartcellcollection) dan menambahkannya ke koleksi.

### Mengembalikan

Seri grafik yang ditambahkan atau seri yang sudah ada di koleksi.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/id/aspose.slides.charts/ichartcellcollection) | Sel-sel yang berisi nama seri. |
| type | [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype) | Tipe yang menentukan tipe seri |

### Catatan

Jika seri grafik dibuat dari sel yang sama sudah ada di koleksi, maka metode tidak menambahkan apa-apa dan mengembalikan indeksnya.


## add(self, name, type) {#str-charttype}
Membuat seri grafik baru dari nilai dan menambahkannya ke koleksi.

### Mengembalikan

Seri grafik yang ditambahkan.



```python
def add(self, name, type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| name | **str** | Nama seri. |
| type | [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype) | Tipe yang menentukan tipe seri |



### Lihat Juga
* enumerasi [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype)
* kelas [`IChartCellCollection`](/slides/python-net/id/aspose.slides.charts/ichartcellcollection)
* kelas [`IChartDataCell`](/slides/python-net/id/aspose.slides.charts/ichartdatacell)
* kelas [`IChartSeries`](/slides/python-net/id/aspose.slides.charts/ichartseries)
* kelas [`IChartSeriesCollection`](/slides/python-net/id/aspose.slides.charts/ichartseriescollection)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)