---
title: cubic_bezier_to method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposeslidespointf-asposeslidespointf-asposeslidespointf}
パスの末尾に立方ベジェ曲線を追加します


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/ja/aspose.slides/pointf) | 最初の方向点 |
| point2 | [`PointF`](/slides/python-net/ja/aspose.slides/pointf) | 2番目の方向点 |
| point3 | [`PointF`](/slides/python-net/ja/aspose.slides/pointf) | 終点 |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposeslidespointf-asposeslidespointf-asposeslidespointf-int}
パスの指定された位置に立方ベジェ曲線を追加します


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/ja/aspose.slides/pointf) | 最初の方向点 |
| point2 | [`PointF`](/slides/python-net/ja/aspose.slides/pointf) | 2番目の方向点 |
| point3 | [`PointF`](/slides/python-net/ja/aspose.slides/pointf) | 終点 |
| index | **int** | PathData 内のセグメントのインデックス |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | セグメントインデックスが PathData の範囲外です |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
パスの末尾に立方ベジェ曲線を追加します


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x1 | **float** | 最初の方向点の X 座標 |
| y1 | **float** | 最初の方向点の Y 座標 |
| x2 | **float** | 2番目の方向点の X 座標 |
| y2 | **float** | 2番目の方向点の Y 座標 |
| x3 | **float** | 終点の X 座標 |
| y3 | **float** | 終点の Y 座標 |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
パスの指定された位置に立方ベジェ曲線を追加します


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x1 | **float** | 最初の方向点の X 座標 |
| y1 | **float** | 最初の方向点の Y 座標 |
| x2 | **float** | 2番目の方向点の X 座標 |
| y2 | **float** | 2番目の方向点の Y 座標 |
| x3 | **float** | 終点の X 座標 |
| y3 | **float** | 終点の Y 座標 |
| index | **int** | PathData 内のセグメントのインデックス |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | セグメントインデックスが PathData の範囲外です |



### 参照
* クラス [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath)
* クラス [`PointF`](/slides/python-net/ja/aspose.slides/pointf)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)