---
title: quadratic_bezier_to method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
パスの末尾に二次ベジェ曲線を追加します


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | 方向点 |
| point2 | **aspose.slides.PointF** | 終点 |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
パスの指定された位置に二次ベジェ曲線を追加します


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | 方向点 |
| point2 | **aspose.slides.PointF** | 終点 |
| index | **int** | PathData 内のセグメントのインデックス |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | セグメントインデックスが PathData の範囲外です |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
パスの末尾に二次ベジェ曲線を追加します


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
パスの指定された位置に二次ベジェ曲線を追加します


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
| index | **int** | PathData 内のセグメントのインデックス |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | セグメントインデックスが PathData の範囲外です |



### 参照
* クラス [`GeometryPath`](/slides/python-net/ja/aspose.slides/geometrypath)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)