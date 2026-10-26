---
title: insert_auto_shape method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
新しい自動図形を作成し、指定されたインデックスで図形コレクションに挿入し、デフォルトのテンプレート書式を適用します。

### 戻り値

The newly created [`IAutoShape`](/slides/python-net/ja/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 新しい自動図形を挿入するゼロベースのインデックス。 |
| shape_type | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) | 挿入する自動図形の[`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)。 |
| x | **float** | 図形フレームのX座標（ポイント単位）。 |
| y | **float** | 図形フレームのY座標（ポイント単位）。 |
| width | **float** | 図形フレームの幅（ポイント単位）。 |
| height | **float** | 図形フレームの高さ（ポイント単位）。 |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
新しい自動図形を作成し、指定されたインデックスで図形コレクションに挿入し、オプションでデフォルトのテンプレートスタイルで初期化します。

### 戻り値

The newly created [`IAutoShape`](/slides/python-net/ja/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 自動図形を挿入するゼロベースのインデックス。 |
| shape_type | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) | 挿入する自動図形の[`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)。 |
| x | **float** | 図形フレームのX座標（ポイント単位）。 |
| y | **float** | 図形フレームのY座標（ポイント単位）。 |
| width | **float** | 図形フレームの幅（ポイント単位）。 |
| height | **float** | 図形フレームの高さ（ポイント単位）。 |
| create_from_template | **bool** | True の場合、デフォルトのテンプレートスタイル（空でない名前、シンプルなスタイル、中央揃えテキストを含む）を適用します。<br/><br/>false の場合、すべてのプロパティがデフォルト値に設定された状態で図形を作成します。 |



### 関連項目
* クラス [`IAutoShape`](/slides/python-net/ja/aspose.slides/iautoshape)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* 列挙体 [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)