---
title: add_auto_shape method
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
デフォルトの書式設定で新しい自動図形を作成し、図形コレクションの末尾に追加します。

### 戻り値
新しく作成された [`IAutoShape`](/slides/python-net/ja/aspose.slides/iautoshape)。

```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) | 追加する自動図形の [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)。 |
| x | **float** | 形状フレームの x 座標（ポイント単位）。 |
| y | **float** | 形状フレームの y 座標（ポイント単位）。 |
| width | **float** | 形状フレームの幅（ポイント単位）。 |
| height | **float** | 形状フレームの高さ（ポイント単位）。 |

## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
新しい自動図形を作成し、図形コレクションの末尾に追加します。必要に応じて、デフォルトのテンプレート書式設定で初期化することもできます。

### 戻り値
新しく作成された [`IAutoShape`](/slides/python-net/ja/aspose.slides/iautoshape)。

```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) | 追加する自動図形の [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)。 |
| x | **float** | 形状フレームの x 座標（ポイント単位）。 |
| y | **float** | 形状フレームの y 座標（ポイント単位）。 |
| width | **float** | 形状フレームの幅（ポイント単位）。 |
| height | **float** | 形状フレームの高さ（ポイント単位）。 |
| create_from_template | **bool** | True を指定すると、デフォルトのテンプレートスタイリング（シンプルスタイル、中央揃えテキスト、空でない名前）を新しい図形に適用します。<br/><br/>false を指定すると、すべてのプロパティがデフォルト値に設定された状態で図形を作成します。 |

### 参考
* クラス [`IAutoShape`](/slides/python-net/ja/aspose.slides/iautoshape)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* 列挙体 [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)