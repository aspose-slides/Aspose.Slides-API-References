---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ishapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
指定されたシェイプのコピーを作成し、指定されたインデックスでシェイプ コレクションに挿入します。 クローンされたシェイプは元の位置とサイズを保持します。

### 戻り値

新しく作成された[`IShape`](/slides/python-net/ja/aspose.slides/ishape)。

```python
def insert_clone(self, index, source_shape):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | クローンされたシェイプを挿入するゼロベースのインデックス。 |
| source_shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | クローンする[`IShape`](/slides/python-net/ja/aspose.slides/ishape)。 |

## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
指定されたシェイプのコピーを作成し、指定されたインデックスでシェイプ コレクションに挿入します。 新しいシェイプは `source_shape` の幅と高さを保持します。

### 戻り値

新しく作成された[`IShape`](/slides/python-net/ja/aspose.slides/ishape)。

```python
def insert_clone(self, index, source_shape, x, y):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | クローンされたシェイプを挿入するゼロベースのインデックス。 |
| source_shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | クローンする[`IShape`](/slides/python-net/ja/aspose.slides/ishape)。 |
| x | **float** | クローンされたシェイプのフレームの x 座標（ポイント）。 |
| y | **float** | クローンされたシェイプのフレームの y 座標（ポイント）。 |

## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
指定されたシェイプのコピーを作成し、指定されたインデックスでシェイプ コレクションに挿入します。

### 戻り値

新しく作成された[`IShape`](/slides/python-net/ja/aspose.slides/ishape)。

```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | クローンされたシェイプを挿入するゼロベースのインデックス。 |
| source_shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | クローンする[`IShape`](/slides/python-net/ja/aspose.slides/ishape)。 |
| x | **float** | クローンされたシェイプのフレームの x 座標（ポイント）。 |
| y | **float** | クローンされたシェイプのフレームの y 座標（ポイント）。 |
| width | **float** | クローンされたシェイプのフレームの幅（ポイント）。 |
| height | **float** | クローンされたシェイプのフレームの高さ（ポイント）。 |

### 参照
* クラス [`IShape`](/slides/python-net/ja/aspose.slides/ishape)
* クラス [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)