---
title: insert_chart method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/shapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Membuat grafik baru, menginisialisasinya dengan data seri contoh dan pengaturan, serta menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

### Returns

Grafik baru yang dibuat [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype) | Tipe grafik yang akan dibuat. |
| x | **float** | Koordinat x grafik baru, dalam poin. |
| y | **float** | Koordinat y grafik baru, dalam poin. |
| width | **float** | Lebar grafik baru, dalam poin. |
| height | **float** | Tinggi grafik baru, dalam poin. |
| index | **int** | Indeks berbasis nol tempat grafik baru disisipkan dalam koleksi bentuk. |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Membuat grafik baru, menginisialisasinya dengan data seri contoh dan pengaturan, serta menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

### Returns

Grafik baru yang dibuat [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype) | Tipe grafik yang akan dibuat. |
| x | **float** | Koordinat x grafik baru, dalam poin. |
| y | **float** | Koordinat y grafik baru, dalam poin. |
| width | **float** | Lebar grafik baru, dalam poin. |
| height | **float** | Tinggi grafik baru, dalam poin. |
| index | **int** | Indeks berbasis nol tempat grafik baru disisipkan dalam koleksi bentuk. |
| init_with_sample | **bool** | True untuk menginisialisasi grafik baru dengan data seri contoh dan pengaturan; false untuk membuat grafik tanpa seri dan hanya dengan pengaturan minimal, yang membuat pembuatan lebih cepat. |



### Lihat Juga
* enumerasi [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype)
* kelas [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart)
* kelas [`ShapeCollection`](/slides/python-net/id/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)