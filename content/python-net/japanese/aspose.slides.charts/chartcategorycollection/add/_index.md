---
title: add method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
コレクションにカテゴリが存在する場合はそれを返します。存在しない場合は [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell) から新しいチャートカテゴリを作成し、コレクションに追加します。

### 戻り値

追加されたカテゴリまたは既存のカテゴリ。

```python
def add(self, chart_data_cell):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell) | チャートカテゴリの作成に使用されるセル。 |

## add(self, value) {#any}
[`ChartCategory`](/slides/python-net/ja/aspose.slides.charts/chartcategory) を値から新しく作成し、コレクションに追加します。

### 戻り値

追加された [`IChartCategory`](/slides/python-net/ja/aspose.slides.charts/ichartcategory)。

```python
def add(self, value):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| value | **any** | 値。 |

### 備考

このメソッドは AUTO_DATA という名前のワークシートを追加し、すべての値をそこに追加します。[`ChartDataWorkbook`](/slides/python-net/ja/aspose.slides.charts/chartdataworkbook) を使用してセルの値を追加または編集する場合は、このワークシートを使用しないようにしてください
            このメソッドで追加できる値の最大数は 16711680 を超えてはいけません

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 上限を超えた場合 |

### 関連項目
* クラス [`ChartCategory`](/slides/python-net/ja/aspose.slides.charts/chartcategory)
* クラス [`ChartCategoryCollection`](/slides/python-net/ja/aspose.slides.charts/chartcategorycollection)
* クラス [`ChartDataWorkbook`](/slides/python-net/ja/aspose.slides.charts/chartdataworkbook)
* クラス [`IChartCategory`](/slides/python-net/ja/aspose.slides.charts/ichartcategory)
* クラス [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)