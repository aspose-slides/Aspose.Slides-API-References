---
title: GetRange()
second_title: Aspose.Slides for C++ API リファレンス
description: チャート データの範囲を取得します。
type: docs
weight: 170
url: /ja/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() メソッド


チャート データの範囲を取得します。

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```


### 戻り値

セル データ範囲の数式。例: \"Sheet1!$A$1:$C$4\"
## 備考




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## 参照

* クラス [String](../../../system/string/)
* クラス [IChartData](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)