---
title: refresh_data method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
チャートデータをソースワークブックから再読み込みして更新します。


```python
def refresh_data(self):
    ...
```


### 備考

チャートが外部ワークブックを使用している場合、呼び出し時にワークブックにアクセスできる必要があります。

### 例外

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | ワークブックの形式がサポートされていない場合、または [`ChartData.data_source_type`](/slides/python-net/ja/aspose.slides.charts/chartdata/data_source_type) が<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/ja/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) で外部ワークブックにアクセスできないかロードできない場合にスローされます。 |



### 参照
* クラス [`ChartData`](/slides/python-net/ja/aspose.slides.charts/chartdata)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)