---
title: quadratic_bezier_to method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
Menambahkan kurva Bezier kuadratik di akhir jalur


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Titik arah |
| point2 | **aspose.slides.PointF** | Titik akhir |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
Menambahkan kurva Bezier kuadratik ke tempat yang ditentukan pada jalur


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Titik arah |
| point2 | **aspose.slides.PointF** | Titik akhir |
| index | **int** | Indeks segmen dalam PathData |

### Exceptions

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Indeks segmen berada di luar jangkauan PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Menambahkan kurva Bezier kuadratik di akhir jalur


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x1 | **float** | Koordinat X titik arah |
| y1 | **float** | Koordinat Y titik arah |
| x2 | **float** | Koordinat X titik akhir |
| y2 | **float** | Koordinat Y titik akhir |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Menambahkan kurva Bezier kuadratik ke tempat yang ditentukan pada jalur


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x1 | **float** | Koordinat X titik arah |
| y1 | **float** | Koordinat Y titik arah |
| x2 | **float** | Koordinat X titik akhir |
| y2 | **float** | Koordinat Y titik akhir |
| index | **int** | Indeks segmen dalam PathData |

### Exceptions

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Indeks segmen berada di luar jangkauan PathData |



### Lihat Juga
* kelas [`GeometryPath`](/slides/python-net/id/aspose.slides/geometrypath)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)