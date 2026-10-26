---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides for C++ API リファレンス
description: Y方向の系列のErrorBarsを表します。
type: docs
weight: 235
url: /ja/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() メソッド

Y方向の系列のErrorBarsを表します。

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## 備考

Y方向のErrorBarsは、area、bar、line、scatter、bubble タイプの系列で利用可能です。その他のチャートタイプでは、このプロパティは null を返します（3D チャートを含む）。カスタム値の場合は、DataPoints コレクションを使用して値を指定します（[IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) プロパティを使用）。

読み取り専用 [IErrorBarsFormat](../../ierrorbarsformat/)。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IErrorBarsFormat](../../ierrorbarsformat/)
* クラス [IChartSeries](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)