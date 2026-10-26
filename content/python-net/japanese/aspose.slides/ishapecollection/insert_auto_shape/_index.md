---
title: insert_auto_shape method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
新しい自動シェイプを作成し、指定されたインデックスでシェイプ コレクションに挿入し、既定のテンプレート書式を適用します。

### 戻り値

新しく作成された [`IAutoShape`](/slides/python-net/ja/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 新しい自動シェイプを挿入するゼロベースのインデックス。 |
| shape_type | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) | 挿入する自動シェイプの [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)。 |
| x | **float** | シェイプのフレームの x 座標（ポイント単位）。 |
| y | **float** | シェイプのフレームの y 座標（ポイント単位）。 |
| width | **float** | シェイプのフレームの幅（ポイント単位）。 |
| height | **float** | シェイプのフレームの高さ（ポイント単位）。 |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
新しい自動シェイプを作成し、指定されたインデックスでシェイプ コレクションに挿入し、必要に応じて既定のテンプレート スタイルで初期化します。

### 戻り値

新しく作成された [`IAutoShape`](/slides/python-net/ja/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | シェイプを挿入するゼロベースのインデックス。 |
| shape_type | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) | 挿入する自動シェイプの [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)。 |
| x | **float** | シェイプのフレームの x 座標（ポイント単位）。 |
| y | **float** | シェイプのフレームの y 座標（ポイント単位）。 |
| width | **float** | シェイプのフレームの幅（ポイント単位）。 |
| height | **float** | シェイプのフレームの高さ（ポイント単位）。 |
| create_from_template | **bool** | True を指定すると既定のテンプレート スタイル（空でない名前、シンプルなスタイル、中央揃えテキストを含む）を適用し、false を指定するとすべてのプロパティがデフォルト値に設定された状態でシェイプを作成します。 |



### 参照
* クラス [`IAutoShape`](/slides/python-net/ja/aspose.slides/iautoshape)
* クラス [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)
* 列挙型 [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)