---
title: insert_connector method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
新しいコネクタ形状を作成し、指定されたインデックスに形状コレクションに挿入し、デフォルトのテンプレートスタイルを適用します。

### 戻り値

新しく作成された[`IConnector`](/slides/python-net/ja/aspose.slides/iconnector)。

```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | **int** | コネクタ形状を挿入するゼロベースのインデックス。 |
| shape_type | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) | 挿入するコネクタ形状の[`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)。 |
| x | **float** | コネクタのフレームの x 座標（ポイント）。 |
| y | **float** | コネクタのフレームの y 座標（ポイント）。 |
| width | **float** | コネクタのフレームの幅（ポイント）。 |
| height | **float** | コネクタのフレームの高さ（ポイント）。 |

## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
新しいコネクタ形状を作成し、指定されたインデックスに形状コレクションに挿入し、オプションでデフォルトのテンプレートスタイルを適用します。

### 戻り値

新しく作成された[`IConnector`](/slides/python-net/ja/aspose.slides/iconnector)。

```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | **int** | コネクタ形状を挿入するゼロベースのインデックス。 |
| shape_type | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) | 挿入するコネクタ形状の[`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)。 |
| x | **float** | コネクタのフレームの x 座標（ポイント）。 |
| y | **float** | コネクタのフレームの y 座標（ポイント）。 |
| width | **float** | コネクタのフレームの幅（ポイント）。 |
| height | **float** | コネクタのフレームの高さ（ポイント）。 |
| create_from_template | **bool** | デフォルトのテンプレートスタイル（空でない名前、シンプルなスタイル）を適用する場合は true、<br/><br/>            デフォルトのプロパティ値でコネクタを作成する場合は false。 |

### 参照
* クラス [`IConnector`](/slides/python-net/ja/aspose.slides/iconnector)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* 列挙型 [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)