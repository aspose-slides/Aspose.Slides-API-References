---
title: cubic_bezier_to method
second_title: Aspose.Slides for Python 透過 .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposeslidespointf-asposeslidespointf-asposeslidespointf}
在路徑的末端新增三次貝塞爾曲線


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf) | 第一方向點 |
| point2 | [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf) | 第二方向點 |
| point3 | [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf) | 終點 |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposeslidespointf-asposeslidespointf-asposeslidespointf-int}
在路徑的指定位置新增三次貝塞爾曲線


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf) | 第一方向點 |
| point2 | [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf) | 第二方向點 |
| point3 | [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf) | 終點 |
| index | **int** | PathData 中段的索引 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段的索引超出 PathData 範圍 |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
在路徑的末端新增三次貝塞爾曲線


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x1 | **float** | 第一方向點的 X 坐標 |
| y1 | **float** | 第一方向點的 Y 坐標 |
| x2 | **float** | 第二方向點的 X 坐標 |
| y2 | **float** | 第二方向點的 Y 坐標 |
| x3 | **float** | 終點的 X 坐標 |
| y3 | **float** | 終點的 Y 坐標 |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
在路徑的指定位置新增三次貝塞爾曲線


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x1 | **float** | 第一方向點的 X 坐標 |
| y1 | **float** | 第一方向點的 Y 坐標 |
| x2 | **float** | 第二方向點的 X 坐標 |
| y2 | **float** | 第二方向點的 Y 坐標 |
| x3 | **float** | 終點的 X 坐標 |
| y3 | **float** | 終點的 Y 坐標 |
| index | **int** | PathData 中段的索引 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段的索引超出 PathData 範圍 |



### 另請參閱
* 類別 [`GeometryPath`](/slides/python-net/zh-hant/aspose.slides/geometrypath)
* 類別 [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)