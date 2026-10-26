---
title: add_auto_shape method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ishapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
デフォルトの書式設定で新しいオート シェイプを作成し、シェイプ コレクションの末尾に追加します。

### 戻り値

新しく作成された[`IAutoShape`](/slides/python-net/ja/aspose.slides/iautoshape)。

```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) | 追加するオート シェイプの[`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)。 |
| x | **float** | シェイプのフレームの x 座標（ポイント単位）。 |
| y | **float** | シェイプのフレームの y 座標（ポイント単位）。 |
| width | **float** | シェイプのフレームの幅（ポイント単位）。 |
| height | **float** | シェイプのフレームの高さ（ポイント単位）。 |

## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
新しいオート シェイプを作成し、シェイプ コレクションの末尾に追加します。オプションで、デフォルトのテンプレート書式で初期化できます。

### 戻り値

新しく作成された[`IAutoShape`](/slides/python-net/ja/aspose.slides/iautoshape)。

```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) | 追加するオート シェイプの[`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)。 |
| x | **float** | シェイプのフレームの x 座標（ポイント単位）。 |
| y | **float** | シェイプのフレームの y 座標（ポイント単位）。 |
| width | **float** | シェイプのフレームの幅（ポイント単位）。 |
| height | **float** | シェイプのフレームの高さ（ポイント単位）。 |
| create_from_template | **bool** | True を指定すると、デフォルトのテンプレート スタイル（シンプル スタイル、中央揃えテキスト、空でない名前）を新しいシェイプに適用します。<br/><br/>false を指定すると、すべてのプロパティがデフォルト値に設定された状態でシェイプが作成されます。 |

### 参照
* クラス [`IAutoShape`](/slides/python-net/ja/aspose.slides/iautoshape)
* クラス [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)
* 列挙体 [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)