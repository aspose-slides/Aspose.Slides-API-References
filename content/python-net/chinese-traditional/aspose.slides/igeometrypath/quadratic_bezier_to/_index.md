---
title: quadratic_bezier_to method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
在路徑末端加入二次貝塞爾曲線


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | 方向點 |
| point2 | **aspose.slides.PointF** | 終點 |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
在路徑的指定位置加入二次貝塞爾曲線


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | 方向點 |
| point2 | **aspose.slides.PointF** | 終點 |
| index | **int** | PathData 中段的索引 |

### Exceptions

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段索引超出 PathData 範圍 |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
在路徑末端加入二次貝塞爾曲線


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x1 | **float** | 方向點的 X 座標 |
| y1 | **float** | 方向點的 Y 座標 |
| x2 | **float** | 終點的 X 座標 |
| y2 | **float** | 終點的 Y 座標 |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
在路徑的指定位置加入二次貝塞爾曲線


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x1 | **float** | 方向點的 X 座標 |
| y1 | **float** | 方向點的 Y 座標 |
| x2 | **float** | 終點的 X 座標 |
| y2 | **float** | 終點的 Y 座標 |
| index | **int** | PathData 中段的索引 |

### Exceptions

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段索引超出 PathData 範圍 |



### See Also
* 類別 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)