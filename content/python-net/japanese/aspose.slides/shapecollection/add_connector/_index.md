---
title: add_connector method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
デフォルトのテンプレートスタイルを使用して新しいコネクタ シェイプを作成し、シェイプ コレクションの末尾に追加します。

### 戻り値

新しく作成された [`IConnector`](/slides/python-net/ja/aspose.slides/iconnector)。

```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) | 追加するコネクタ シェイプの [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)。 |
| x | **float** | コネクタのフレームの x 座標（ポイント単位）。 |
| y | **float** | コネクタのフレームの y 座標（ポイント単位）。 |
| width | **float** | コネクタのフレームの幅（ポイント単位）。 |
| height | **float** | コネクタのフレームの高さ（ポイント単位）。 |

## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
新しいコネクタ シェイプを作成し、シェイプ コレクションの末尾に追加します。必要に応じてデフォルトのテンプレートスタイルを適用します。

### 戻り値

新しく作成された [`IConnector`](/slides/python-net/ja/aspose.slides/iconnector)。

```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) | 作成するコネクタ シェイプの [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)。 |
| x | **float** | コネクタのフレームの x 座標（ポイント単位）。 |
| y | **float** | コネクタのフレームの y 座標（ポイント単位）。 |
| width | **float** | コネクタのフレームの幅（ポイント単位）。 |
| height | **float** | コネクタのフレームの高さ（ポイント単位）。 |
| create_from_template | **bool** | true はデフォルトのテンプレートスタイル（名前が空でない、シンプルなスタイル）を適用します。<br/><br/>false はデフォルトのプロパティ値でコネクタを作成します。 |

### 参照
* クラス [`IConnector`](/slides/python-net/ja/aspose.slides/iconnector)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* 列挙型 [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)