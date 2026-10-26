---
title: add_chart method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/ishapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, serta menambahkannya ke akhir koleksi shape.

### Mengembalikan

[`IChart`](/slides/python-net/id/aspose.slides.charts/ichart) yang baru dibuat.



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype) | Jenis chart yang akan ditambahkan. |
| x | **float** | Koordinat x chart baru, dalam poin. |
| y | **float** | Koordinat y chart baru, dalam poin. |
| width | **float** | Lebar chart, dalam poin. |
| height | **float** | Tinggi chart, dalam poin. |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, serta menambahkannya ke akhir koleksi shape.

### Mengembalikan

[`IChart`](/slides/python-net/id/aspose.slides.charts/ichart) yang baru dibuat.



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype) | Jenis chart yang akan ditambahkan. |
| x | **float** | Koordinat x chart baru, dalam poin. |
| y | **float** | Koordinat y chart baru, dalam poin. |
| width | **float** | Lebar chart, dalam poin. |
| height | **float** | Tinggi chart, dalam poin. |
| init_with_sample | **bool** | True untuk menginisialisasi chart baru dengan data seri contoh dan pengaturan; <br/><br/>false untuk membuat chart tanpa seri dan hanya pengaturan minimal, yang membuat pembuatan lebih cepat. |



### Lihat Juga
* enumeration [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype)
* class [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart)
* class [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)