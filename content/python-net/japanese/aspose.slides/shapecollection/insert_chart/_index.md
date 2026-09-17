---
title: insert_chart method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、指定したインデックスでシェイプ コレクションに挿入します。

### 戻り値

新しく作成された[`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart)です。

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
| index | **int** | シェイプ コレクションに新しいチャートを挿入するゼロベースのインデックス。 |

## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、指定したインデックスでシェイプ コレクションに挿入します。

### 戻り値

新しく作成された[`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart)です。

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
| index | **int** | シェイプ コレクションに新しいチャートを挿入するゼロベースのインデックス。 |
| init_with_sample | **bool** | True はサンプルシリーズデータと設定で新しいチャートを初期化します。 <br/><br/> false はシリーズなしで最小限の設定だけでチャートを作成し、作成が速くなります。 |

### 参照
* 列挙体 [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype)
* クラス [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)