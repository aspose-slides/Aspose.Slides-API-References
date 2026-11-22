---
title: refresh_data method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
元のブックから再読み込みしてチャート データを更新します。


```python
def refresh_data(self):
    ...
```


### 備考

チャートが外部ブックを使用している場合、呼び出し時にブックにアクセスできる必要があります。

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | ワークブックの形式がサポートされていない場合、または [`IChartData.data_source_type`](/slides/python-net/ja/aspose.slides.charts/ichartdata/data_source_type) が<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/ja/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) で、外部ワークブックにアクセスできない、またはロードできない場合にスローされます。 |



### 参照
* クラス [`IChartData`](/slides/python-net/ja/aspose.slides.charts/ichartdata)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)