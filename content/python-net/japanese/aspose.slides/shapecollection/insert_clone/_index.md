---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
指定されたシェイプのコピーを作成し、指定されたインデックスでシェイプコレクションに挿入します。
クローンされたシェイプは元の位置とサイズを保持します。

### 戻り値

新しく作成された [`IShape`](/slides/python-net/ja/aspose.slides/ishape)。

```python
def insert_clone(self, index, source_shape):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 挿入先となるクローンシェイプのゼロベースインデックス。 |
| source_shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | クローン対象の [`IShape`](/slides/python-net/ja/aspose.slides/ishape)。 |

## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
指定されたシェイプのコピーを作成し、指定されたインデックスでシェイプコレクションに挿入します。
新しいシェイプは `source_shape` の幅と高さを保持します。

### 戻り値

新しく作成された [`IShape`](/slides/python-net/ja/aspose.slides/ishape)。

```python
def insert_clone(self, index, source_shape, x, y):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 挿入先となるクローンシェイプのゼロベースインデックス。 |
| source_shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | クローン対象の [`IShape`](/slides/python-net/ja/aspose.slides/ishape)。 |
| x | **float** | クローンシェイプのフレームの x 座標（ポイント単位）。 |
| y | **float** | クローンシェイプのフレームの y 座標（ポイント単位）。 |

## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
指定されたシェイプのコピーを作成し、指定されたインデックスでシェイプコレクションに挿入します。

### 戻り値

新しく作成された [`IShape`](/slides/python-net/ja/aspose.slides/ishape)。

```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 挿入先となるクローンシェイプのゼロベースインデックス。 |
| source_shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | クローン対象の [`IShape`](/slides/python-net/ja/aspose.slides/ishape)。 |
| x | **float** | クローンシェイプのフレームの x 座標（ポイント単位）。 |
| y | **float** | クローンシェイプのフレームの y 座標（ポイント単位）。 |
| width | **float** | クローンシェイプのフレームの幅（ポイント単位）。 |
| height | **float** | クローンシェイプのフレームの高さ（ポイント単位）。 |

### 参照
* クラス [`IShape`](/slides/python-net/ja/aspose.slides/ishape)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)