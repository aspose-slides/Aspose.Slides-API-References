---
title: line_to method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposeslidespointf}
在路徑末端加入直線


```python
def line_to(self, point):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf) | 直線的終點 |


## line_to(self, x, y) {#float-float}
在路徑末端加入直線


```python
def line_to(self, x, y):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x | **float** | 直線終點的 X 坐標 |
| y | **float** | 直線終點的 Y 坐標 |


## line_to(self, point, index) {#asposeslidespointf-int}
在路徑的指定位置加入直線


```python
def line_to(self, point, index):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf) | 終點 |
| index | **int** | PathData 中段的索引 |

### 例外情況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段的索引超出 PathData 範圍 |


## line_to(self, x, y, index) {#float-float-int}
在路徑的指定位置加入直線


```python
def line_to(self, x, y, index):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x | **float** | 點的 X 坐標 |
| y | **float** | 點的 Y 坐標 |
| index | **int** | PathData 中段的索引 |

### 例外情況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段的索引超出 PathData 範圍 |



### 另請參閱
* 類別 [`GeometryPath`](/slides/python-net/zh-hant/aspose.slides/geometrypath)
* 類別 [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)