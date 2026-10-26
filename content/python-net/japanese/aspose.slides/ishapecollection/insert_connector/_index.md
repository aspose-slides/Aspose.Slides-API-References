---
title: insert_connector method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ishapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
新しいコネクタ シェイプを作成し、指定されたインデックスでシェイプ コレクションに挿入し、デフォルトのテンプレート スタイルを適用します。

### 戻り値

新しく作成された[`IConnector`](/slides/python-net/ja/aspose.slides/iconnector)。

```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | **int** | コネクタ シェイプを挿入するゼロベースのインデックス。 |
| shape_type | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) | 挿入するコネクタ シェイプの[`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)。 |
| x | **float** | コネクタのフレームの X 座標（ポイント単位）。 |
| y | **float** | コネクタのフレームの Y 座標（ポイント単位）。 |
| width | **float** | コネクタのフレームの幅（ポイント単位）。 |
| height | **float** | コネクタのフレームの高さ（ポイント単位）。 |

## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
新しいコネクタ シェイプを作成し、指定されたインデックスでシェイプ コレクションに挿入し、オプションでデフォルトのテンプレート スタイルを適用します。

### 戻り値

新しく作成された[`IConnector`](/slides/python-net/ja/aspose.slides/iconnector)。

```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | **int** | コネクタ シェイプを挿入するゼロベースのインデックス。 |
| shape_type | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) | 挿入するコネクタ シェイプの[`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)。 |
| x | **float** | コネクタのフレームの X 座標（ポイント単位）。 |
| y | **float** | コネクタのフレームの Y 座標（ポイント単位）。 |
| width | **float** | コネクタのフレームの幅（ポイント単位）。 |
| height | **float** | コネクタのフレームの高さ（ポイント単位）。 |
| create_from_template | **bool** | True を指定するとデフォルトのテンプレート スタイル（非空の名前、シンプルなスタイル）を適用します;<br/><br/>false を指定するとコネクタをデフォルトのプロパティ値で作成します。 |

### 参照
* クラス [`IConnector`](/slides/python-net/ja/aspose.slides/iconnector)
* クラス [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)
* 列挙型 [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)