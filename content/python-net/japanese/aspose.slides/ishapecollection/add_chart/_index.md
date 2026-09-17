---
title: add_chart method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ishapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
新しい chart を作成し、サンプルシリーズ データと設定で初期化し、shape コレクションの末尾に追加します。

### 戻り値
新しく作成された [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart)。

```python
def add_chart(self, type, x, y, width, height):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype) | 追加する chart の種類。 |
| x | **float** | 新しい chart の x 座標（ポイント単位）。 |
| y | **float** | 新しい chart の y 座標（ポイント単位）。 |
| width | **float** | chart の幅（ポイント単位）。 |
| height | **float** | chart の高さ（ポイント単位）。 |

## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
新しい chart を作成し、サンプルシリーズ データと設定で初期化し、shape コレクションの末尾に追加します。

### 戻り値
新しく作成された [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart)。

```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype) | 追加する chart の種類。 |
| x | **float** | 新しい chart の x 座標（ポイント単位）。 |
| y | **float** | 新しい chart の y 座標（ポイント単位）。 |
| width | **float** | chart の幅（ポイント単位）。 |
| height | **float** | chart の高さ（ポイント単位）。 |
| init_with_sample | **bool** | サンプルシリーズ データと設定で新しい chart を初期化する場合は true、<br/><br/>シリーズなしで最小設定のみで chart を作成し、作成速度を向上させる場合は false。 |

### 関連項目
* 列挙 [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype)
* クラス [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart)
* クラス [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)