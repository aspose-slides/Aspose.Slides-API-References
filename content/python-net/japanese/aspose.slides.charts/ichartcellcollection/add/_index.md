---
title: add method
second_title: Aspose.Slides for Python via .NET API リファレンス
description:
type: docs
url: /ja/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
コレクションに新しいセルを追加します。

```python
def add(self, chart_data_cell):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell) | 追加する新しいセル。 |

## add(self, value) {#any}
指定された値から [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell) を作成し、コレクションに追加します。

```python
def add(self, value):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| value | **any** | その値。 |

### 備考

このメソッドは名前が AUTO_DATA のワークシートを追加し、すべての値をそこに追加します。  [`IChartDataWorkbook`](/slides/python-net/ja/aspose.slides.charts/ichartdataworkbook) を使用して Cell の値を追加または編集する場合、このワークシートを使用しないようにしてください。  
このメソッドで追加できる値の最大数は 16711680 を超えてはいけません。

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 制限を超えた場合 |

### 参照
* クラス [`IChartCellCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcellcollection)
* クラス [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell)
* クラス [`IChartDataWorkbook`](/slides/python-net/ja/aspose.slides.charts/ichartdataworkbook)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)