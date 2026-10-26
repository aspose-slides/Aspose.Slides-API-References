---
title: ErrorBarsFormat class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat クラス

チャートシリーズの誤差バーを表します。ErrorBars のカスタム値は IChartDataPointCollection にあります ([`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) プロパティ内)。

ErrorBarsFormat 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`type`](/slides/python-net/ja/aspose.slides.charts/errorbarsformat/type/) | 誤差バーのタイプを取得または設定します。 <br/>            読み取り/書き込み [`ErrorBarType`](/slides/python-net/ja/aspose.slides.charts/errorbartype)。 |
| [`value_type`](/slides/python-net/ja/aspose.slides.charts/errorbarsformat/value_type/) | 誤差バーの長さを決定する可能な方法を表します。 <br/>            カスタム値タイプの場合は、シリーズの DataPoints コレクション内の特定データポイントの [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) プロパティを使用して値を指定します。<br/>            Fixed、Percentage、StandardDeviation の値タイプの場合は、Value プロパティを使用して値を指定します。  <br/>            読み取り/書き込み [`ErrorBarValueType`](/slides/python-net/ja/aspose.slides.charts/errorbarvaluetype)。 |
| [`has_end_cap`](/slides/python-net/ja/aspose.slides.charts/errorbarsformat/has_end_cap/) | 誤差バーの端にキャップが描画されないことを指定します。<br/>            読み取り/書き込み **bool**。 |
| [`value`](/slides/python-net/ja/aspose.slides.charts/errorbarsformat/value/) | Fixed、Percentage、StandardDeviation の値タイプで使用され、誤差バーの長さを決定する値を取得または設定します。 <br/>            その他の場合は NaN を返します。<br/>            読み取り/書き込み **float**。 |
| [`format`](/slides/python-net/ja/aspose.slides.charts/errorbarsformat/format/) | 誤差バーの書式を表します。<br/>            読み取り/書き込み [`IFormat`](/slides/python-net/ja/aspose.slides.charts/iformat)。 |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/errorbarsformat/chart/) | 親チャートを返します。<br/>            読み取り専用 [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart)。 |
| [`is_visible`](/slides/python-net/ja/aspose.slides.charts/errorbarsformat/is_visible/) | 誤差バーの表示状態を取得または設定します。<br/>            読み取り/書き込み **bool**。 |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/errorbarsformat/presentation/) |  |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)