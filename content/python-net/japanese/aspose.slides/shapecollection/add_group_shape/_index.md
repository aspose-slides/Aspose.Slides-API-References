---
title: add_group_shape method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
新しい空のグループ シェイプを作成し、シェイプ コレクションの末尾に追加します。グループのフレームは、追加されたシェイプに合わせて自動的に調整されます。

### 戻り値

新しく作成された [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape)。

```python
def add_group_shape(self):
    ...
```

## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
新しいグループ シェイプを作成し、指定された SVG 画像を個々のシェイプに変換し、結果として得られたグループをシェイプ コレクションの末尾に追加します。

### 戻り値

新しく作成された [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape)。

```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/ja/aspose.slides/isvgimage) | ベクター コンテンツをシェイプに変換するための [`ISvgImage`](/slides/python-net/ja/aspose.slides/isvgimage)。 |
| x | **float** | ポイント単位のグループのフレームの x 座標です。 |
| y | **float** | ポイント単位のグループのフレームの y 座標です。 |
| width | **float** | ポイント単位のグループのフレームの幅です。 |
| height | **float** | ポイント単位のグループのフレームの高さです。 |

### 参照
* クラス [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape)
* クラス [`ISvgImage`](/slides/python-net/ja/aspose.slides/isvgimage)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)