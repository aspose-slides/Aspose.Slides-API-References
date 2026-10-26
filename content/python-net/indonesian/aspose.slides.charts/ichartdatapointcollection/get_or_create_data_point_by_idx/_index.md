---
title: get_or_create_data_point_by_idx method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/ichartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
Jika koleksi sudah berisi titik data dengan indeks `index`, maka mengembalikan titik data ini.
            Jika koleksi tidak berisi titik data dengan indeks `index`==N (ketika jumlah titik data dalam koleksi ini kurang atau sama dengan N) maka menambahkan titik data yang kurang dan mengembalikan yang terakhir (yang memiliki indeks yang diminta).
            Misalnya, indeks koleksi adalah {0, 1, 2}, dan indeks yang diminta adalah 5.
            Kemudian metode menambahkan titik data yang kurang: {0, 1, 2, 3, 4, 5}. Dan mengembalikan titik data dengan indeks 5.

### Mengembalikan

Mengembalikan titik data dengan indeks yang diminta.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks. |



### Lihat Juga
* kelas [`IChartDataPoint`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint)
* kelas [`IChartDataPointCollection`](/slides/python-net/id/aspose.slides.charts/ichartdatapointcollection)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)