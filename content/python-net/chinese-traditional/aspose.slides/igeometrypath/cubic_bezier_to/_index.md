---
title: cubic_bezier_to method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
在路徑的末端添加三次貝塞爾曲線


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | 第一個方向點 |
| point2 | **aspose.slides.PointF** | 第二個方向點 |
| point3 | **aspose.slides.PointF** | 結束點 |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
將三次貝塞爾曲線添加到路徑的指定位置


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | 第一個方向點 |
| point2 | **aspose.slides.PointF** | 第二個方向點 |
| point3 | **aspose.slides.PointF** | 結束點 |
| index | **int** | PathData 中段的索引 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段索引超出 PathData 範圍 |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
在路徑的末端添加三次貝塞爾曲線


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x1 | **float** | 第一個方向點的 X 坐標 |
| y1 | **float** | 第一個方向點的 Y 坐標 |
| x2 | **float** | 第二個方向點的 X 坐標 |
| y2 | **float** | 第二個方向點的 Y 坐標 |
| x3 | **float** | 結束點的 X 坐標 |
| y3 | **float** | 結束點的 Y 坐標 |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
將三次貝塞爾曲線添加到路徑的指定位置


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x1 | **float** | 第一個方向點的 X 坐標 |
| y1 | **float** | 第一個方向點的 Y 坐標 |
| x2 | **float** | 第二個方向點的 X 坐標 |
| y2 | **float** | 第二個方向點的 Y 坐標 |
| x3 | **float** | 結束點的 X 坐標 |
| y3 | **float** | 結束點的 Y 坐標 |
| index | **int** | PathData 中段的索引 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段索引超出 PathData 範圍 |



### 另請參閱
* 類別 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)