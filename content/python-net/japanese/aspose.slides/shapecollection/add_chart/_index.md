---
title: add_chart method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
新しいチャートを作成し、サンプル系列データと設定で初期化し、シェイプ コレクションの末尾に追加します。

### 戻り値

新しく作成された [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype) | 追加するチャートのタイプ。 |
| x | **float** | 新しいチャートの x 座標（ポイント単位）。 |
| y | **float** | 新しいチャートの y 座標（ポイント単位）。 |
| width | **float** | チャートの幅（ポイント単位）。 |
| height | **float** | チャートの高さ（ポイント単位）。 |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
新しいチャートを作成し、サンプル系列データと設定で初期化し、シェイプ コレクションの末尾に追加します。

### 戻り値

新しく作成された [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype) | 追加するチャートのタイプ。 |
| x | **float** | 新しいチャートの x 座標（ポイント単位）。 |
| y | **float** | 新しいチャートの y 座標（ポイント単位）。 |
| width | **float** | チャートの幅（ポイント単位）。 |
| height | **float** | チャートの高さ（ポイント単位）。 |
| init_with_sample | **bool** | True は新しいチャートをサンプル系列データと設定で初期化します; <br/><br/>            false は系列なし、最小限の設定のみでチャートを作成し、作成を高速化します。 |



### 参照
* 列挙体 [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype)
* クラス [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)