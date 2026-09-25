---
title: contains method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
指定された点がこの矩形に含まれているかどうかを判定します。

### 戻り値

`True` の場合、点がこの矩形に含まれます。それ以外の場合は `False`。



```python
def contains(self, point):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/ja/aspose.slides/point) | テスト対象の点。`x` と `y` 属性を持つ任意のオブジェクトが受け入れられます。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **TypeError** | 引数の数が間違っています。 |


## contains(self, rect) {#rectangle}
`rect` で表される矩形領域がこの矩形に完全に含まれているかどうかを判定します。

### 戻り値

`True` の場合、`rect` で表される矩形領域がこの矩形に完全に含まれています。それ以外の場合は `False`。



```python
def contains(self, rect):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/ja/aspose.slides/rectangle) | テスト対象の矩形。`x`、`y`、`width`、`height` の属性を持つ任意のオブジェクトが受け入れられます。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **TypeError** | 引数の数が間違っています。 |


## contains(self, x, y) {#int-int}
指定された点がこの矩形に含まれているかどうかを判定します。

### 戻り値

`True` の場合、`x` と `y` で定義された点がこの矩形に含まれています。それ以外の場合は `False`。



```python
def contains(self, x, y):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x | **int** | テスト対象の点の x 座標。 |
| y | **int** | テスト対象の点の y 座標。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **TypeError** | 引数の数が間違っています。 |



### 参照
* クラス [`Point`](/slides/python-net/ja/aspose.slides/point)
* クラス [`Rectangle`](/slides/python-net/ja/aspose.slides/rectangle)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)