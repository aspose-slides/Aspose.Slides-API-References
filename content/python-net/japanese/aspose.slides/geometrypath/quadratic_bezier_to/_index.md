---
title: quadratic_bezier_to method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
パスの終点に二次ベジエ曲線を追加します


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/ja/aspose.slides/pointf) | 方向点 |
| point2 | [`PointF`](/slides/python-net/ja/aspose.slides/pointf) | 終点 |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
パスの指定した位置に二次ベジエ曲線を追加します


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/ja/aspose.slides/pointf) | 方向点 |
| point2 | [`PointF`](/slides/python-net/ja/aspose.slides/pointf) | 終点 |
| index | **int** | PathData のセグメントのインデックス |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | セグメントインデックスが PathData の範囲外です |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
パスの終点に二次ベジエ曲線を追加します


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x1 | **float** | 方向点の X 座標 |
| y1 | **float** | 方向点の Y 座標 |
| x2 | **float** | 終点の X 座標 |
| y2 | **float** | 終点の Y 座標 |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
パスの指定した位置に二次ベジエ曲線を追加します


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x1 | **float** | 方向点の X 座標 |
| y1 | **float** | 方向点の Y 座標 |
| x2 | **float** | 終点の X 座標 |
| y2 | **float** | 終点の Y 座標 |
| index | **int** | PathData のセグメントのインデックス |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | セグメントインデックスが PathData の範囲外です |



### 関連項目
* class [`GeometryPath`](/slides/python-net/ja/aspose.slides/geometrypath)
* class [`PointF`](/slides/python-net/ja/aspose.slides/pointf)
* module [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)