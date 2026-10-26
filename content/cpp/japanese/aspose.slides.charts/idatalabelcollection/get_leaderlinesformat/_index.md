---
title: get_LeaderLinesFormat()
second_title: Aspose.Slides for C++ API リファレンス
description: データ ラベルのリーダーライン形式を表します。読み取り専用 IChartLinesFormat.
type: docs
weight: 14
url: /ja/aspose.slides.charts/idatalabelcollection/get_leaderlinesformat/
---
## IDataLabelCollection::get_LeaderLinesFormat() メソッド

データ ラベルのリーダーライン形式を表します。読み取り専用 [IChartLinesFormat](../../ichartlinesformat/)。

```cpp
virtual System::SharedPtr<IChartLinesFormat> Aspose::Slides::Charts::IDataLabelCollection::get_LeaderLinesFormat()=0
```

## 備考

例: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IChart> chart = System::ExplicitCast<IChart>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
System::SharedPtr<IDataLabelCollection> labels = series->idx_get(0)->get_Labels();
System::SharedPtr<ILineFillFormat> fillFormat = labels->get_LeaderLinesFormat()->get_Line()->get_FillFormat();

fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::FromArgb(255, 255, 0, 0));
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChartLinesFormat](../../ichartlinesformat/)
* クラス [IDataLabelCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)