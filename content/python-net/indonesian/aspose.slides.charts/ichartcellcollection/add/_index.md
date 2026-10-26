---
title: add method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Tambahkan sel baru ke koleksi.

```python
def add(self, chart_data_cell):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/id/aspose.slides.charts/ichartdatacell) | Sel baru yang akan ditambahkan. |

## add(self, value) {#any}
Membuat [`IChartDataCell`](/slides/python-net/id/aspose.slides.charts/ichartdatacell) dari nilai yang ditentukan dan menambahkannya ke koleksi.

```python
def add(self, value):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | **any** | Nilainya. |

### Keterangan

Metode ini menambahkan lembar kerja dengan nama AUTO_DATA dan menambahkan semua nilai di sana.  Jika Anda menggunakan [`IChartDataWorkbook`](/slides/python-net/id/aspose.slides.charts/ichartdataworkbook) untuk menambahkan atau mengedit nilai Cell, pastikan bahwa Anda tidak menggunakan lembar kerja ini
            Jumlah maksimum nilai yang ditambahkan menggunakan metode ini tidak boleh melebihi 16711680

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | jika batas terlampaui |

### Lihat Juga
* kelas [`IChartCellCollection`](/slides/python-net/id/aspose.slides.charts/ichartcellcollection)
* kelas [`IChartDataCell`](/slides/python-net/id/aspose.slides.charts/ichartdatacell)
* kelas [`IChartDataWorkbook`](/slides/python-net/id/aspose.slides.charts/ichartdataworkbook)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)