---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides for C++ API リファレンス
description: Y方向の系列のErrorBarsを表します。
type: docs
weight: 235
url: /ja/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() メソッド


Y方向の系列のErrorBarsを表します。

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## 備考


Y方向のErrorBarsは、エリア、バー、ライン、散布図、バブルのタイプの系列で利用できます。他のすべてのチャートタイプでは、このプロパティはnullを返します（3Dチャートを含む）。カスタム値を使用する場合は、DataPointsコレクションで値を指定してください（[IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)プロパティを使用）。

読み取り専用 [IErrorBarsFormat](../../ierrorbarsformat/). 
## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IErrorBarsFormat](../../ierrorbarsformat/)
* クラス [ChartSeries](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)