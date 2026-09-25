---
title: line_to method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposeslidespointf}
Yolun sonuna bir çizgi ekler


```python
def line_to(self, point):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/tr/aspose.slides/pointf) | Çizginin son noktası |


## line_to(self, x, y) {#float-float}
Yolun sonuna bir çizgi ekler


```python
def line_to(self, x, y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | **float** | Çizginin son noktasının X koordinatı |
| y | **float** | Çizginin son noktasının Y koordinatı |


## line_to(self, point, index) {#asposeslidespointf-int}
Yolun belirtilen yerine bir çizgi ekler


```python
def line_to(self, point, index):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/tr/aspose.slides/pointf) | Son nokta |
| index | **int** | PathData içindeki segmentin indeksi |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment indeksi PathData aralığının dışındadır |


## line_to(self, x, y, index) {#float-float-int}
Yolun belirtilen yerine bir çizgi ekler


```python
def line_to(self, x, y, index):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | **float** | Noktanın X koordinatı |
| y | **float** | Noktanın Y koordinatı |
| index | **int** | PathData içindeki segmentin indeksi |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment indeksi PathData aralığının dışındadır |



### İlgili
* sınıf [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath)
* sınıf [`PointF`](/slides/python-net/tr/aspose.slides/pointf)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)