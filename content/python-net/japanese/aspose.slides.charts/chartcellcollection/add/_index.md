---
title: add method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
コレクションに新しいセルを追加します。


```python
def add(self, cell):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell) | 追加する新しいセル。 |


## add(self, value) {#any}
指定された値から[`ChartDataCell`](/slides/python-net/ja/aspose.slides.charts/chartdatacell)を作成し、コレクションに追加します。


```python
def add(self, value):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| value | **any** | 値。 |

### 備考

このメソッドは名前が AUTO_DATA のワークシートを追加し、すべての値をそこに追加します。[`ChartDataWorkbook`](/slides/python-net/ja/aspose.slides.charts/chartdataworkbook) を使用してセルの値を追加または編集する場合は、このワークシートを使用しないでください。  
    使用できる値の最大数は 16711680 を超えてはなりません

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 上限を超えた場合 |



### 参照
* クラス [`ChartCellCollection`](/slides/python-net/ja/aspose.slides.charts/chartcellcollection)
* クラス [`ChartDataCell`](/slides/python-net/ja/aspose.slides.charts/chartdatacell)
* クラス [`ChartDataWorkbook`](/slides/python-net/ja/aspose.slides.charts/chartdataworkbook)
* クラス [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)