---
title: add method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
コレクションにカテゴリが存在する場合はそれを返します。存在しない場合は [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell) から新しいチャートカテゴリを作成し、コレクションに追加します。

### 戻り値

追加されたまたは既存のカテゴリ。

```python
def add(self, chart_data_cell):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell) | チャートカテゴリ作成に使用するセル。 |

## add(self, value) {#any}
値から新しい [`IChartCategory`](/slides/python-net/ja/aspose.slides.charts/ichartcategory) を作成し、コレクションに追加します。

### 戻り値

追加された [`IChartCategory`](/slides/python-net/ja/aspose.slides.charts/ichartcategory)。

```python
def add(self, value):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| value | **any** | 値。 |

### 備考

このメソッドは名前が AUTO_DATA のワークシートを追加し、すべての値をそこに追加します。[`IChartDataWorkbook`](/slides/python-net/ja/aspose.slides.charts/ichartdataworkbook) を使用してセルの値を追加または編集する場合は、このワークシートを使用しないでください。 このメソッドで追加できる値の最大数は 16711680 を超えてはいけません。

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 制限を超えた場合 |

### 参照
* クラス [`IChartCategory`](/slides/python-net/ja/aspose.slides.charts/ichartcategory)
* クラス [`IChartCategoryCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection)
* クラス [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell)
* クラス [`IChartDataWorkbook`](/slides/python-net/ja/aspose.slides.charts/ichartdataworkbook)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)