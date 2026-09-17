---
title: quadratic_bezier_to method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
パスの末尾に二次ベジエ曲線を追加します


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Direction point |
| point2 | **aspose.slides.PointF** | End point |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
パスの指定された位置に二次ベジエ曲線を追加します


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Direction point |
| point2 | **aspose.slides.PointF** | End point |
| index | **int** | Index of segment in PathData |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | セグメントインデックスが PathData の範囲外です |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
パスの末尾に二次ベジエ曲線を追加します


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| x1 | **float** | X coordinate of direction point |
| y1 | **float** | Y coordinate of direction point |
| x2 | **float** | X coordinate of end point |
| y2 | **float** | Y coordinate of end point |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
パスの指定された位置に二次ベジエ曲線を追加します


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| x1 | **float** | X coordinate of direction point |
| y1 | **float** | Y coordinate of direction point |
| x2 | **float** | X coordinate of end point |
| y2 | **float** | Y coordinate of end point |
| index | **int** | Index of segment in PathData |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | セグメントインデックスが PathData の範囲外です |



### 参照
* クラス [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)