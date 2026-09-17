---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ishapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。
クローンされたシェイプは元の位置とサイズを保持します。

### Returns

新しく作成された [`IShape`](/slides/python-net/ja/aspose.slides/ishape)。

```python
def add_clone(self, source_shape):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | クローンする [`IShape`](/slides/python-net/ja/aspose.slides/ishape)。 |

## add_clone(self, source_shape, x, y) {#ishape-float-float}
指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。
新しいシェイプは `source_shape` の幅と高さを保持します。

### Returns

新しく作成された [`IShape`](/slides/python-net/ja/aspose.slides/ishape)。

```python
def add_clone(self, source_shape, x, y):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | クローンする [`IShape`](/slides/python-net/ja/aspose.slides/ishape)。 |
| x | **float** | クローンされたシェイプのフレームの x 座標（ポイント）。 |
| y | **float** | クローンされたシェイプのフレームの y 座標（ポイント）。 |

## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。

### Returns

新しく作成された [`IShape`](/slides/python-net/ja/aspose.slides/ishape)。

```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | クローンするシェイプ。 |
| x | **float** | クローンされたシェイプのフレームの x 座標（ポイント）。 |
| y | **float** | クローンされたシェイプのフレームの y 座標（ポイント）。 |
| width | **float** | クローンされたシェイプのフレームの幅（ポイント）。 |
| height | **float** | クローンされたシェイプのフレームの高さ（ポイント）。 |

### See Also
* クラス [`IShape`](/slides/python-net/ja/aspose.slides/ishape)
* クラス [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)