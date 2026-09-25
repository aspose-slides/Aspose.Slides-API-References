---
title: contains method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
指定された点がこの矩形に含まれているかどうかを判断します。

### 戻り値

`True` は点がこの矩形に含まれている場合、そうでなければ `False`。

```python
def contains(self, point):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/ja/aspose.slides/pointf) | テスト対象の点。`x` と `y` 属性を持つ任意のオブジェクトが受け入れられます。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **TypeError** | 引数の数が間違っています。 |

## contains(self, rect) {#rectanglef}
`rect` で表される矩形領域がこの矩形に完全に含まれているかどうかを判断します。

### 戻り値

`True` は `rect` で表される矩形領域がこの矩形に完全に含まれている場合、そうでなければ `False`。

```python
def contains(self, rect):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef) | テスト対象の矩形。`x`、`y`、`width`、`height` 属性を持つ任意のオブジェクトが受け入れられます。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **TypeError** | 引数の数が間違っています。 |

## contains(self, x, y) {#float-float}
指定された点がこの矩形に含まれているかどうかを判断します。

### 戻り値

`True` は `x` と `y` で定義された点がこの矩形に含まれている場合、そうでなければ `False`。

```python
def contains(self, x, y):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x | **float** | テスト対象の点の x 座標。 |
| y | **float** | テスト対象の点の y 座標。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **TypeError** | 引数の数が間違っています。 |

### 参照
* クラス [`PointF`](/slides/python-net/ja/aspose.slides/pointf)
* クラス [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)