---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides for C++ API リファレンス
description: X方向のシリーズのErrorBarsを表します。
type: docs
weight: 222
url: /ja/aspose.slides.charts/ichartseries/get_errorbarsxformat/
---
## IChartSeries::get_ErrorBarsXFormat() メソッド

X方向のシリーズのErrorBarsを表します。

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsXFormat()=0
```

## 備考

X方向のErrorBarsは、エリア、棒、散布図、バブル タイプのシリーズで使用できます。  
他のすべてのチャートタイプでは、このプロパティは null を返します（3D チャートを含む）。  
カスタム値を使用する場合は、DataPoints コレクションで値を指定してください（[IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) プロパティを使用）。

読み取り専用 [IErrorBarsFormat](../../ierrorbarsformat/)。 
## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IErrorBarsFormat](../../ierrorbarsformat/)
* クラス [IChartSeries](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)