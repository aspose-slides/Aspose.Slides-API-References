---
title: cubic_bezier_to method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
Menambahkan kurva Bezier kubik di akhir jalur


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Titik arah pertama |
| point2 | **aspose.slides.PointF** | Titik arah kedua |
| point3 | **aspose.slides.PointF** | Titik akhir |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
Menambahkan kurva Bezier kubik ke tempat yang ditentukan pada jalur


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Titik arah pertama |
| point2 | **aspose.slides.PointF** | Titik arah kedua |
| point3 | **aspose.slides.PointF** | Titik akhir |
| index | **int** | Indeks segmen dalam PathData |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Indeks segmen berada di luar rentang PathData |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Menambahkan kurva Bezier kubik di akhir jalur


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x1 | **float** | Koordinat X titik arah pertama |
| y1 | **float** | Koordinat Y titik arah pertama |
| x2 | **float** | Koordinat X titik arah kedua |
| y2 | **float** | Koordinat Y titik arah kedua |
| x3 | **float** | Koordinat X titik akhir |
| y3 | **float** | Koordinat Y titik akhir |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Menambahkan kurva Bezier kubik ke tempat yang ditentukan pada jalur


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x1 | **float** | Koordinat X titik arah pertama |
| y1 | **float** | Koordinat Y titik arah pertama |
| x2 | **float** | Koordinat X titik arah kedua |
| y2 | **float** | Koordinat Y titik arah kedua |
| x3 | **float** | Koordinat X titik akhir |
| y3 | **float** | Koordinat Y titik akhir |
| index | **int** | Indeks segmen dalam PathData |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Indeks segmen berada di luar rentang PathData |



### Lihat Juga
* kelas [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)