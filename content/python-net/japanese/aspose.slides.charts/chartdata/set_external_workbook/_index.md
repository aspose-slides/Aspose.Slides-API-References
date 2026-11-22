---
title: set_external_workbook method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
外部ブックブックをチャートのデータ ソースとして設定します。チャート データは対象ブックブックから更新されます。


```python
def set_external_workbook(self, workbook_path):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| workbook_path | **str** | 対象ブックブックへのパス |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 外部ブックブックが利用できないか、読み込めません。 |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
外部ブックブックをチャートのデータ ソースとして設定します。


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| workbook_path | **str** | 対象ブックブックへのパス |
| update_chart_data | **bool** | 値が false の場合、ブックブックのパスのみが更新されます。<br/><br/>チャート データは対象ブックブックから読み込まれず、更新もされません。対象ブックブックが存在しない場合や利用できない場合に使用できます。<br/><br/>値が true の場合、チャート データは対象ブックブックから更新されます。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 外部ブックブックが利用できないか、読み込めません。 |



### 参照
* クラス [`ChartData`](/slides/python-net/ja/aspose.slides.charts/chartdata)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)