---
title: add method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
Tambahkan sel baru ke koleksi.


```python
def add(self, cell):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/id/aspose.slides.charts/ichartdatacell) | Sel baru yang akan ditambahkan. |


## add(self, value) {#any}
Membuat [`ChartDataCell`](/slides/python-net/id/aspose.slides.charts/chartdatacell) dari nilai yang ditentukan dan menambahkannya ke koleksi.


```python
def add(self, value):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | **any** | Nilainya. |

### Catatan

Metode ini menambahkan lembar kerja dengan nama AUTO_DATA dan menambahkan semua nilai ke sana.  Jika Anda menggunakan [`ChartDataWorkbook`](/slides/python-net/id/aspose.slides.charts/chartdataworkbook) untuk menambah atau mengedit nilai Sel, pastikan Anda tidak menggunakan lembar kerja ini
            Jumlah maksimum nilai yang ditambahkan menggunakan metode ini tidak boleh melebihi 16711680

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | jika batas terlampaui |



### Lihat Juga
* kelas [`ChartCellCollection`](/slides/python-net/id/aspose.slides.charts/chartcellcollection)
* kelas [`ChartDataCell`](/slides/python-net/id/aspose.slides.charts/chartdatacell)
* kelas [`ChartDataWorkbook`](/slides/python-net/id/aspose.slides.charts/chartdataworkbook)
* kelas [`IChartDataCell`](/slides/python-net/id/aspose.slides.charts/ichartdatacell)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)