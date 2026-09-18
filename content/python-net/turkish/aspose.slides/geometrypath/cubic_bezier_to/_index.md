---
title: cubic_bezier_to method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
Yolun sonuna kübik Bezier eğrisi ekler


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | İlk yön noktası |
| point2 | **aspose.slides.PointF** | İkinci yön noktası |
| point3 | **aspose.slides.PointF** | Bitiş noktası |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
Yolun belirtilen konumuna kübik Bezier eğrisi ekler


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | İlk yön noktası |
| point2 | **aspose.slides.PointF** | İkinci yön noktası |
| point3 | **aspose.slides.PointF** | Bitiş noktası |
| index | **int** | PathData içindeki segmentin indeksi |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment indeksi PathData aralığının dışında |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Yolun sonuna kübik Bezier eğrisi ekler


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x1 | **float** | İlk yön noktasının X koordinatı |
| y1 | **float** | İlk yön noktasının Y koordinatı |
| x2 | **float** | İkinci yön noktasının X koordinatı |
| y2 | **float** | İkinci yön noktasının Y koordinatı |
| x3 | **float** | Bitiş noktasının X koordinatı |
| y3 | **float** | Bitiş noktasının Y koordinatı |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Yolun belirtilen konumuna kübik Bezier eğrisi ekler


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x1 | **float** | İlk yön noktasının X koordinatı |
| y1 | **float** | İlk yön noktasının Y koordinatı |
| x2 | **float** | İkinci yön noktasının X koordinatı |
| y2 | **float** | İkinci yön noktasının Y koordinatı |
| x3 | **float** | Bitiş noktasının X koordinatı |
| y3 | **float** | Bitiş noktasının Y koordinatı |
| index | **int** | PathData içindeki segmentin indeksi |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment indeksi PathData aralığının dışında |



### Ayrıca Bakınız
* sınıf [`GeometryPath`](/slides/python-net/tr/aspose.slides/geometrypath)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)