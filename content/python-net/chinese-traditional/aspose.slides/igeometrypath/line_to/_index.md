---
title: line_to method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposeslidespointf}
在路徑的末端新增線條


```python
def line_to(self, point):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf) | 線條的終點 |


## line_to(self, x, y) {#float-float}
在路徑的末端新增線條


```python
def line_to(self, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | 線條終點的 X 座標 |
| y | **float** | 線條終點的 Y 座標 |


## line_to(self, point, index) {#asposeslidespointf-int}
在路徑的指定位置新增線條


```python
def line_to(self, point, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf) | 終點 |
| index | **int** | PathData 中段的索引 |

### 例外情況

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段的索引超出 PathData 範圍 |


## line_to(self, x, y, index) {#float-float-int}
在路徑的指定位置新增線條


```python
def line_to(self, x, y, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | 點的 X 座標 |
| y | **float** | 點的 Y 座標 |
| index | **int** | PathData 中段的索引 |

### 例外情況

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段的索引超出 PathData 範圍 |



### 另請參閱
* 類別 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath)
* 類別 [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)