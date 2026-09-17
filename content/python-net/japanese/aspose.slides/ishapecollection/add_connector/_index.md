---
title: add_connector method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
デフォルトのテンプレートスタイルを適用した新しいコネクタ形状を作成し、シェイプコレクションの末尾に追加します。

### 戻り値

新しく作成された [`IConnector`](/slides/python-net/ja/aspose.slides/iconnector)。

```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) | 追加するコネクタ形状の [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)。 |
| x | **float** | コネクタのフレームのx座標（ポイント）。 |
| y | **float** | コネクタのフレームのy座標（ポイント）。 |
| width | **float** | コネクタのフレームの幅（ポイント）。 |
| height | **float** | コネクタのフレームの高さ（ポイント）。 |

## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
新しいコネクタ形状を作成し、シェイプコレクションの末尾に追加します。オプションでデフォルトのテンプレートスタイルを適用できます。

### 戻り値

新しく作成された [`IConnector`](/slides/python-net/ja/aspose.slides/iconnector)。

```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) | 作成するコネクタ形状の [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)。 |
| x | **float** | コネクタのフレームのx座標（ポイント）。 |
| y | **float** | コネクタのフレームのy座標（ポイント）。 |
| width | **float** | コネクタのフレームの幅（ポイント）。 |
| height | **float** | コネクタのフレームの高さ（ポイント）。 |
| create_from_template | **bool** | デフォルトのテンプレートスタイル（名前が空でなく、シンプルなスタイル）を適用する場合は true。<br/><br/>            デフォルトのプロパティ値でコネクタを作成する場合は false。 |

### 参照
* クラス [`IConnector`](/slides/python-net/ja/aspose.slides/iconnector)
* クラス [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)
* 列挙体 [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)