---
title: line_to method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposeslidespointf}
Menambahkan garis ke akhir jalur


```python
def line_to(self, point):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/id/aspose.slides/pointf) | Titik akhir dari garis |


## line_to(self, x, y) {#float-float}
Menambahkan garis ke akhir jalur


```python
def line_to(self, x, y):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | **float** | Koordinat X dari titik akhir garis |
| y | **float** | Koordinat Y dari titik akhir garis |


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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Indeks segmen berada di luar jangkauan PathData |


## line_to(self, x, y, index) {#float-float-int}
Menambahkan garis ke tempat yang ditentukan pada jalur


```python
def line_to(self, x, y, index):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | **float** | Koordinat X dari titik |
| y | **float** | Koordinat Y dari titik |
| index | **int** | Indeks segmen dalam PathData |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Indeks segmen berada di luar jangkauan PathData |



### Lihat Juga
* kelas [`GeometryPath`](/slides/python-net/id/aspose.slides/geometrypath)
* kelas [`PointF`](/slides/python-net/id/aspose.slides/pointf)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)