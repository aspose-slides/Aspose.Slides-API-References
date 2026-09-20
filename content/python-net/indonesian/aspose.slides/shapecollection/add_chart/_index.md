---
title: add_chart method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/shapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, serta menambahkannya ke akhir koleksi shape.

### Mengembalikan

[`IChart`](/slides/python-net/id/aspose.slides.charts/ichart) yang baru dibuat.



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype) | Tipe chart yang akan ditambahkan. |
| x | **float** | Koordinat x dari chart baru, dalam point. |
| y | **float** | Koordinat y dari chart baru, dalam point. |
| width | **float** | Lebar chart, dalam point. |
| height | **float** | Tinggi chart, dalam point. |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, serta menambahkannya ke akhir koleksi shape.

### Mengembalikan

[`IChart`](/slides/python-net/id/aspose.slides.charts/ichart) yang baru dibuat.



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype) | Tipe chart yang akan ditambahkan. |
| x | **float** | Koordinat x dari chart baru, dalam point. |
| y | **float** | Koordinat y dari chart baru, dalam point. |
| width | **float** | Lebar chart, dalam point. |
| height | **float** | Tinggi chart, dalam point. |
| init_with_sample | **bool** | True untuk menginisialisasi chart baru dengan data seri contoh dan pengaturan; <br/><br/>            false untuk membuat chart tanpa seri dan hanya pengaturan minimal, yang mempercepat pembuatan. |



### Lihat Juga
* enumerasi [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype)
* kelas [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart)
* kelas [`ShapeCollection`](/slides/python-net/id/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)