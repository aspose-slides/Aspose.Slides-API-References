---
title: cubic_bezier_to method
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
パスの末尾にキュービックベジェ曲線を追加します


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | 最初の方向点 |
| point2 | **aspose.slides.PointF** | 2番目の方向点 |
| point3 | **aspose.slides.PointF** | 終点 |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
パスの指定された位置にキュービックベジェ曲線を追加します


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | 最初の方向点 |
| point2 | **aspose.slides.PointF** | 2番目の方向点 |
| point3 | **aspose.slides.PointF** | 終点 |
| index | **int** | PathData内のセグメントのインデックス |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | セグメントインデックスがPathDataの範囲外です |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
パスの末尾にキュービックベジェ曲線を追加します


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x1 | **float** | 最初の方向点のX座標 |
| y1 | **float** | 最初の方向点のY座標 |
| x2 | **float** | 2番目の方向点のX座標 |
| y2 | **float** | 2番目の方向点のY座標 |
| x3 | **float** | 終点のX座標 |
| y3 | **float** | 終点のY座標 |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
パスの指定された位置にキュービックベジェ曲線を追加します


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x1 | **float** | 最初の方向点のX座標 |
| y1 | **float** | 最初の方向点のY座標 |
| x2 | **float** | 2番目の方向点のX座標 |
| y2 | **float** | 2番目の方向点のY座標 |
| x3 | **float** | 終点のX座標 |
| y3 | **float** | 終点のY座標 |
| index | **int** | PathData内のセグメントのインデックス |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | セグメントインデックスがPathDataの範囲外です |



### 参照
* クラス [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)