---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides for C++ API リファレンス
description: X 方向の系列の ErrorBars を表します。
type: docs
weight: 222
url: /ja/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() メソッド


X 方向の系列の ErrorBars を表します。

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## 備考

X 方向の ErrorBars は、area、bar、scatter、bubble タイプの系列で利用可能です。その他のチャートタイプ（3D チャートを含む）では、このプロパティは null を返します。カスタム値を使用する場合は、DataPoints コレクションを使用して値を指定してください（[IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) プロパティを使用）。

読み取り専用 [IErrorBarsFormat](../../ierrorbarsformat/)。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IErrorBarsFormat](../../ierrorbarsformat/)
* クラス [ChartSeries](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)