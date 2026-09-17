---
title: IErrorBarsFormat class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ierrorbarsformat/
---
## IErrorBarsFormat クラス

チャート系列の誤差バーを表します。ErrorBars のカスタム値は IChartDataPointCollection にあります ([`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) プロパティ内)。

IErrorBarsFormat 型は以下のメンバーを公開します：

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`type`](/slides/python-net/ja/aspose.slides.charts/ierrorbarsformat/type/) | 誤差バーのタイプを取得または設定します。 <br/>            読み取り/書き込み [`ErrorBarType`](/slides/python-net/ja/aspose.slides.charts/errorbartype)。 |
| [`value_type`](/slides/python-net/ja/aspose.slides.charts/ierrorbarsformat/value_type/) | 誤差バーの長さを決定する可能な方法を表します。 <br/>            カスタム値タイプの場合、シリーズの DataPoints コレクション内の特定のデータポイントの [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) プロパティを使用して値を指定します。  <br/>            読み取り/書き込み [`ErrorBarValueType`](/slides/python-net/ja/aspose.slides.charts/errorbarvaluetype)。 |
| [`has_end_cap`](/slides/python-net/ja/aspose.slides.charts/ierrorbarsformat/has_end_cap/) | 誤差バーの端部キャップが描画されないことを指定します。<br/>            読み取り/書き込み **bool**。 |
| [`value`](/slides/python-net/ja/aspose.slides.charts/ierrorbarsformat/value/) | Fixed、Percentage、StandardDeviation の値タイプと共に使用され、誤差バーの長さを決定する値を取得または設定します。 <br/>            読み取り/書き込み **float**。 |
| [`format`](/slides/python-net/ja/aspose.slides.charts/ierrorbarsformat/format/) | 誤差バーの書式を表します。<br/>            読み取り/書き込み [`IFormat`](/slides/python-net/ja/aspose.slides.charts/iformat)。 |
| [`is_visible`](/slides/python-net/ja/aspose.slides.charts/ierrorbarsformat/is_visible/) | Error Bars の可視性を取得または設定します。<br/>            読み取り/書き込み **bool**。 |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/ierrorbarsformat/chart/) |  |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/ierrorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/ierrorbarsformat/presentation/) |  |


### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)