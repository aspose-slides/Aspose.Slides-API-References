---
title: quadratic_bezier_to method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
Yolun sonuna ikinci dereceli Bezier eğrisi ekler


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/tr/aspose.slides/pointf) | Yön noktası |
| point2 | [`PointF`](/slides/python-net/tr/aspose.slides/pointf) | Bitiş noktası |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
Yolun belirtilen konumuna ikinci dereceli Bezier eğrisi ekler


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/tr/aspose.slides/pointf) | Yön noktası |
| point2 | [`PointF`](/slides/python-net/tr/aspose.slides/pointf) | Bitiş noktası |
| index | **int** | PathData içindeki segmentin indeksi |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment indeksi PathData aralığının dışında |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Yolun sonuna ikinci dereceli Bezier eğrisi ekler


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x1 | **float** | Yön noktasının X koordinatı |
| y1 | **float** | Yön noktasının Y koordinatı |
| x2 | **float** | Bitiş noktasının X koordinatı |
| y2 | **float** | Bitiş noktasının Y koordinatı |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Yolun belirtilen konumuna ikinci dereceli Bezier eğrisi ekler


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x1 | **float** | Yön noktasının X koordinatı |
| y1 | **float** | Yön noktasının Y koordinatı |
| x2 | **float** | Bitiş noktasının X koordinatı |
| y2 | **float** | Bitiş noktasının Y koordinatı |
| index | **int** | PathData içindeki segmentin indeksi |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment indeksi PathData aralığının dışında |



### Bakınız
* sınıf [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath)
* sınıf [`PointF`](/slides/python-net/tr/aspose.slides/pointf)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)