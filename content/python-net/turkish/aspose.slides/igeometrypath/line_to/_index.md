---
title: line_to method
second_title: Aspose.Slides için .NET üzerinden Python API Referansı
description: 
type: docs
url: /tr/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposepydrawingpointf}
Yolun sonuna bir çizgi ekler

```python
def line_to(self, point):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Çizginin son noktası |

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

## line_to(self, point, index) {#asposepydrawingpointf-int}
Yolun belirtilen konumuna bir çizgi ekler

```python
def line_to(self, point, index):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Son nokta |
| index | **int** | PathData içindeki segmentin indeksi |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment indeksi PathData aralığının dışındadır |

## line_to(self, x, y, index) {#float-float-int}
Yolun belirtilen konumuna bir çizgi ekler

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
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)