---
title: insert_chart method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ishapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、  
            指定されたインデックスでシェイプコレクションに挿入します。

### Returns

新しく作成された[`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart)。

```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype) | 作成するチャートのタイプ。 |
| x | **float** | 新しいチャートの x 座標（ポイント単位）。 |
| y | **float** | 新しいチャートの y 座標（ポイント単位）。 |
| width | **float** | 新しいチャートの幅（ポイント単位）。 |
| height | **float** | 新しいチャートの高さ（ポイント単位）。 |
| index | **int** | シェイプコレクションに新しいチャートを挿入するゼロベースのインデックス。 |

## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、  
            指定されたインデックスでシェイプコレクションに挿入します。

### Returns

新しく作成された[`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart)。

```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype) | 作成するチャートのタイプ。 |
| x | **float** | 新しいチャートの x 座標（ポイント単位）。 |
| y | **float** | 新しいチャートの y 座標（ポイント単位）。 |
| width | **float** | 新しいチャートの幅（ポイント単位）。 |
| height | **float** | 新しいチャートの高さ（ポイント単位）。 |
| index | **int** | シェイプコレクションに新しいチャートを挿入するゼロベースのインデックス。 |
| init_with_sample | **bool** | サンプルシリーズデータと設定で新しいチャートを初期化する場合は true; <br/><br/>            false の場合はシリーズなしで最小限の設定だけでチャートを作成し、作成が高速になります。 |

### See Also
* 列挙型 [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype)
* クラス [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart)
* クラス [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)