---
title: line_to method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposepydrawingpointf}
パスの末端に線を追加します


```python
def line_to(self, point):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | **aspose.slides.PointF** | 線の終点 |


## line_to(self, x, y) {#float-float}
パスの末端に線を追加します


```python
def line_to(self, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | 線の終点の X 座標 |
| y | **float** | 線の終点の Y 座標 |


## line_to(self, point, index) {#asposepydrawingpointf-int}
指定した場所に線を追加します


```python
def line_to(self, point, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | **aspose.slides.PointF** | 終点 |
| index | **int** | PathData のセグメントのインデックス |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | セグメントインデックスが PathData の範囲外です |


## line_to(self, x, y, index) {#float-float-int}
指定した場所に線を追加します


```python
def line_to(self, x, y, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | 点の X 座標 |
| y | **float** | 点の Y 座標 |
| index | **int** | PathData のセグメントのインデックス |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | セグメントインデックスが PathData の範囲外です |



### See Also
* クラス [`GeometryPath`](/slides/python-net/ja/aspose.slides/geometrypath)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)