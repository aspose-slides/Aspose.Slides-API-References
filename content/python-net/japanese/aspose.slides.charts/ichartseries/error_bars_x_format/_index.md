---
title: error_bars_x_format property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartseries/error_bars_x_format/
weight: 110
---
## error_bars_x_format プロパティ
X 方向の系列の ErrorBars を表します。

    X 方向の ErrorBars は、area、bar、scatter、bubble タイプの系列で利用可能です。
    その他のすべてのチャートタイプでは、このプロパティは None を返します（3D チャートを含む）。
    カスタム値を使用する場合は、DataPoints コレクションを使用して値を指定します
    （[`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) プロパティを使用）。

    読み取り専用 [`IErrorBarsFormat`](/slides/python-net/ja/aspose.slides.charts/ierrorbarsformat)。

### 定義:
```python
@property
def error_bars_x_format(self):
    ...
```


### 参照
* クラス [`IChartSeries`](/slides/python-net/ja/aspose.slides.charts/ichartseries)
* クラス [`IErrorBarsFormat`](/slides/python-net/ja/aspose.slides.charts/ierrorbarsformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)