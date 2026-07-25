---
title: get_Overlap()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 2-D チャート上でバーと列がどれだけ重なるかをパーセンテージ（-100% から 100%）で指定します。
type: docs
weight: 157
url: /ja/aspose.slides.charts/chartseriesgroup/get_overlap/
---
## ChartSeriesGroup::get_Overlap() メソッド

2-D チャート上でバーと列がどれだけ重なるかをパーセンテージ（-100% から 100%）で指定します。

```cpp
int8_t Aspose::Slides::Charts::ChartSeriesGroup::get_Overlap() override
```

## 備考

* -100%: 最大間隔（バーが完全に分離しています）。
* 0%: バーが重なりも間隔もなく並んでいます。
* 100%: 最大重なり（バーが完全に互いに重なります）。このプロパティは読み書き **int8_t** です。

以下の例は、チャート系列グループのオーバーラップを設定し、フォーム上に結果のチャートをレンダリングする方法を示しています: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // オーバーラップを 55% に設定

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## 参照

* クラス [ChartSeriesGroup](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)