---
title: line_to method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposepydrawingpointf}
在路徑的末端添加線段


```python
def line_to(self, point):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| point | **aspose.slides.PointF** | 線段的終點 |


## line_to(self, x, y) {#float-float}
在路徑的末端添加線段


```python
def line_to(self, x, y):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x | **float** | 線段終點的 X 座標 |
| y | **float** | 線段終點的 Y 座標 |


## line_to(self, point, index) {#asposepydrawingpointf-int}
在路徑的指定位置添加線段


```python
def line_to(self, point, index):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| point | **aspose.slides.PointF** | 終點 |
| index | **int** | PathData 中段的索引 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段索引超出 PathData 範圍 |


## line_to(self, x, y, index) {#float-float-int}
在路徑的指定位置添加線段


```python
def line_to(self, x, y, index):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x | **float** | 點的 X 座標 |
| y | **float** | 點的 Y 座標 |
| index | **int** | PathData 中段的索引 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段索引超出 PathData 範圍 |



### 另請參閱
* 類別 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)