---
title: line_to method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposeslidespointf}
Menambahkan garis ke akhir jalur


```python
def line_to(self, point):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/id/aspose.slides/pointf) | Titik akhir garis |


## line_to(self, x, y) {#float-float}
Menambahkan garis ke akhir jalur


```python
def line_to(self, x, y):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | **float** | Koordinat X titik akhir garis |
| y | **float** | Koordinat Y titik akhir garis |


## line_to(self, point, index) {#asposeslidespointf-int}
Menambahkan garis ke tempat yang ditentukan pada jalur


```python
def line_to(self, point, index):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/id/aspose.slides/pointf) | Titik akhir |
| index | **int** | Indeks segmen dalam PathData |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Indeks segmen berada di luar rentang PathData |


## line_to(self, x, y, index) {#float-float-int}
Menambahkan garis ke tempat yang ditentukan pada jalur


```python
def line_to(self, x, y, index):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | **float** | Koordinat X titik |
| y | **float** | Koordinat Y titik |
| index | **int** | Indeks segmen dalam PathData |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Indeks segmen berada di luar rentang PathData |



### Lihat Juga
* kelas [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath)
* kelas [`PointF`](/slides/python-net/id/aspose.slides/pointf)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)