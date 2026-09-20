---
title: line_to method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposepydrawingpointf}
Menambahkan garis ke akhir jalur


```python
def line_to(self, point):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Titik akhir garis |


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


## line_to(self, point, index) {#asposepydrawingpointf-int}
Menambahkan garis ke tempat tertentu pada jalur


```python
def line_to(self, point, index):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Titik akhir |
| index | **int** | Indeks segmen dalam PathData |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Indeks segmen berada di luar rentang PathData |


## line_to(self, x, y, index) {#float-float-int}
Menambahkan garis ke tempat tertentu pada jalur


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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Indeks segmen berada di luar rentang PathData |



### Lihat Juga
* kelas [`GeometryPath`](/slides/python-net/id/aspose.slides/geometrypath)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)