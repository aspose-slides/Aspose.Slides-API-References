---
title: add method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Jika kategori ada dalam koleksi, kembalikan. Jika tidak, buat kategori diagram baru dari [`IChartDataCell`](/slides/python-net/id/aspose.slides.charts/ichartdatacell) dan tambahkan ke koleksi.

### Mengembalikan

Kategori yang ditambahkan atau yang sudah ada.



```python
def add(self, chart_data_cell):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/id/aspose.slides.charts/ichartdatacell) | Cell digunakan untuk membuat kategori diagram. |


## add(self, value) {#any}
Membuat [`ChartCategory`](/slides/python-net/id/aspose.slides.charts/chartcategory) baru dari nilai dan menambahkannya ke koleksi.

### Mengembalikan

Ditambahkan [`IChartCategory`](/slides/python-net/id/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | **any** | Nilainya. |

### Catatan

Metode ini menambahkan lembar kerja dengan nama AUTO_DATA dan menambahkan semua nilai ke sana. Jika Anda menggunakan [`ChartDataWorkbook`](/slides/python-net/id/aspose.slides.charts/chartdataworkbook) untuk menambah atau mengedit nilai sel, pastikan Anda tidak menggunakan lembar kerja ini. Jumlah maksimum nilai yang ditambahkan menggunakan metode ini tidak boleh melebihi 16711680

### Pengecualian

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | jika batas terlampaui |



### Lihat Juga
* kelas [`ChartCategory`](/slides/python-net/id/aspose.slides.charts/chartcategory)
* kelas [`ChartCategoryCollection`](/slides/python-net/id/aspose.slides.charts/chartcategorycollection)
* kelas [`ChartDataWorkbook`](/slides/python-net/id/aspose.slides.charts/chartdataworkbook)
* kelas [`IChartCategory`](/slides/python-net/id/aspose.slides.charts/ichartcategory)
* kelas [`IChartDataCell`](/slides/python-net/id/aspose.slides.charts/ichartdatacell)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)