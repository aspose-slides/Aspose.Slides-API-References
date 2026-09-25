---
title: line_to method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposeslidespointf}
パスの末尾に線を追加します

```python
def line_to(self, point):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/ja/aspose.slides/pointf) | 線の終点 |

## line_to(self, x, y) {#float-float}
パスの末尾に線を追加します

```python
def line_to(self, x, y):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x | **float** | 線の終点のX座標 |
| y | **float** | 線の終点のY座標 |

## line_to(self, point, index) {#asposeslidespointf-int}
パスの指定された位置に線を追加します

```python
def line_to(self, point, index):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/ja/aspose.slides/pointf) | 終点 |
| index | **int** | PathData内のセグメントのインデックス |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | セグメントインデックスがPathDataの範囲外です |

## line_to(self, x, y, index) {#float-float-int}
パスの指定された位置に線を追加します

```python
def line_to(self, x, y, index):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x | **float** | 点のX座標 |
| y | **float** | 点のY座標 |
| index | **int** | PathData内のセグメントのインデックス |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | セグメントインデックスがPathDataの範囲外です |

### 参照
* クラス [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath)
* クラス [`PointF`](/slides/python-net/ja/aspose.slides/pointf)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)