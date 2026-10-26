---
title: add method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides.charts/chartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Membuat chart series baru dan menambahkannya ke koleksi.

### Mengembalikan

Chart series baru.



```python
def add(self, type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype) | Tipe seri |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Membuat chart series baru dari [`ChartDataCell`](/slides/python-net/id/aspose.slides.charts/chartdatacell) dan menambahkannya ke koleksi.

### Mengembalikan

Chart series yang ditambahkan atau seri yang sudah ada di koleksi.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/id/aspose.slides.charts/ichartdatacell) | Sel yang berisi nama seri. |
| type | [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype) | Tipe yang menentukan tipe seri |

### Catatan

Jika chart series dibuat dari sel yang sama sudah ada di koleksi 
            maka metode tidak menambahkan apa pun dan mengembalikan indeksnya.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Membuat chart series baru dari [`ChartCellCollection`](/slides/python-net/id/aspose.slides.charts/chartcellcollection) dan menambahkannya ke koleksi.

### Mengembalikan

Chart series yang ditambahkan atau seri yang sudah ada di koleksi.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/id/aspose.slides.charts/ichartcellcollection) | Sel-sel yang berisi nama seri. |
| type | [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype) | Tipe yang menentukan tipe seri |

### Catatan

Jika chart series dibuat dari sel yang sama sudah ada di koleksi 
            maka metode tidak menambahkan apa pun dan mengembalikan indeksnya.


## add(self, name, type) {#str-charttype}
Membuat chart series baru dari nilai dan menambahkannya ke koleksi.

### Mengembalikan

Chart series yang ditambahkan.



```python
def add(self, name, type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| name | **str** | Nama seri. |
| type | [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype) | Tipe yang menentukan tipe seri |



### Lihat Juga
* class [`ChartCellCollection`](/slides/python-net/id/aspose.slides.charts/chartcellcollection)
* class [`ChartDataCell`](/slides/python-net/id/aspose.slides.charts/chartdatacell)
* class [`ChartSeriesCollection`](/slides/python-net/id/aspose.slides.charts/chartseriescollection)
* enumeration [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype)
* class [`IChartCellCollection`](/slides/python-net/id/aspose.slides.charts/ichartcellcollection)
* class [`IChartDataCell`](/slides/python-net/id/aspose.slides.charts/ichartdatacell)
* class [`IChartSeries`](/slides/python-net/id/aspose.slides.charts/ichartseries)
* module [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)