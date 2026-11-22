---
title: set_external_workbook method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
外部ブックをチャートのデータ ソースとして設定します。チャート データは対象のブックから更新されます。


```python
def set_external_workbook(self, workbook_path):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| workbook_path | **str** | 対象ブックへのパス |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 外部ブックが利用できないか、ロードできません。 |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
外部ブックをチャートのデータ ソースとして設定します。


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| workbook_path | **str** | 対象ブックへのパス |
| update_chart_data | **bool** | false の場合、ブック パスのみが更新されます。<br/><br/>             チャート データは対象のブックから読み込まれず、更新されません。対象のブックが存在しない、または利用できない場合に使用できます。<br/><br/>             true の場合、チャート データは対象のブックから更新されます。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 外部ブックが利用できないか、ロードできません。 |



### 参照
* クラス [`IChartData`](/slides/python-net/ja/aspose.slides.charts/ichartdata)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)