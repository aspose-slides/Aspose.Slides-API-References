---
title: quadratic_bezier_to method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
在路徑末端添加二次貝塞爾曲線


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf) | 方向點 |
| point2 | [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf) | 終點 |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
在路徑的指定位置添加二次貝塞爾曲線


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf) | 方向點 |
| point2 | [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf) | 終點 |
| index | **int** | PathData 中段的索引 |

### 例外

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段索引超出 PathData 範圍 |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
在路徑末端添加二次貝塞爾曲線


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x1 | **float** | 方向點的 X 坐標 |
| y1 | **float** | 方向點的 Y 坐標 |
| x2 | **float** | 終點的 X 坐標 |
| y2 | **float** | 終點的 Y 坐標 |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
在路徑的指定位置添加二次貝塞爾曲線


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x1 | **float** | 方向點的 X 坐標 |
| y1 | **float** | 方向點的 Y 坐標 |
| x2 | **float** | 終點的 X 坐標 |
| y2 | **float** | 終點的 Y 坐標 |
| index | **int** | PathData 中段的索引 |

### 例外

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段索引超出 PathData 範圍 |



### 另請參閱
* 類別 [`GeometryPath`](/slides/python-net/zh-hant/aspose.slides/geometrypath)
* 類別 [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)