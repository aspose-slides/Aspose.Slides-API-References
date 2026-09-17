---
title: cubic_bezier_to method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
パスの末尾に三次ベジェ曲線を追加します


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | First direction point |
| point2 | **aspose.slides.PointF** | Second direction point |
| point3 | **aspose.slides.PointF** | End point |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
パスの指定された位置に三次ベジェ曲線を追加します


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | First direction point |
| point2 | **aspose.slides.PointF** | Second direction point |
| point3 | **aspose.slides.PointF** | End point |
| index | **int** | Index of segment in PathData |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | セグメントインデックスが PathData の範囲外です |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
パスの末尾に三次ベジェ曲線を追加します


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x1 | **float** | X coordinate of first direction point |
| y1 | **float** | Y coordinate of first direction point |
| x2 | **float** | X coordinate of second direction point |
| y2 | **float** | Y coordinate of second direction point |
| x3 | **float** | X coordinate of end point |
| y3 | **float** | Y coordinate of end point |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
パスの指定された位置に三次ベジェ曲線を追加します


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x1 | **float** | X coordinate of first direction point |
| y1 | **float** | Y coordinate of first direction point |
| x2 | **float** | X coordinate of second direction point |
| y2 | **float** | Y coordinate of second direction point |
| x3 | **float** | X coordinate of end point |
| y3 | **float** | Y coordinate of end point |
| index | **int** | Index of segment in PathData |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | セグメントインデックスが PathData の範囲外です |



### 参照
* クラス [`GeometryPath`](/slides/python-net/ja/aspose.slides/geometrypath)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)