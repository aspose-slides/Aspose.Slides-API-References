---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。
クローンされたシェイプは元の位置とサイズを保持します。

### 戻り値

新しく作成された [`IShape`](/slides/python-net/ja/aspose.slides/ishape).



```python
def add_clone(self, source_shape):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | クローンする [`IShape`](/slides/python-net/ja/aspose.slides/ishape)。 |


## add_clone(self, source_shape, x, y) {#ishape-float-float}
指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。
新しいシェイプは `source_shape` の幅と高さを保持します。

### 戻り値

新しく作成された [`IShape`](/slides/python-net/ja/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | クローンするシェイプ。 |
| x | **float** | 新しいシェイプのフレームの x 座標（ポイント単位）。 |
| y | **float** | 新しいシェイプのフレームの y 座標（ポイント単位）。 |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。

### 戻り値

新しく作成された [`IShape`](/slides/python-net/ja/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | クローンするシェイプ。 |
| x | **float** | 新しいシェイプのフレームの x 座標（ポイント単位）。 |
| y | **float** | 新しいシェイプのフレームの y 座標（ポイント単位）。 |
| width | **float** | 新しいシェイプのフレームの幅（ポイント単位）。 |
| height | **float** | 新しいシェイプのフレームの高さ（ポイント単位）。 |



### 参照
* クラス [`IShape`](/slides/python-net/ja/aspose.slides/ishape)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)