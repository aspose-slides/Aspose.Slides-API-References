---
title: set_Overlap()
second_title: Aspose.Slides for C++ API リファレンス
description: 2 次元チャートにおける棒と列の重なり具合をパーセンテージで指定します（-100% から 100% まで）。
type: docs
weight: 170
url: /ja/aspose.slides.charts/chartseriesgroup/set_overlap/
---
## ChartSeriesGroup::set_Overlap(int8_t) メソッド

2 次元チャートにおける棒グラフと柱状グラフの重なり具合をパーセンテージで指定します（-100% から 100% まで）。

```cpp
void Aspose::Slides::Charts::ChartSeriesGroup::set_Overlap(int8_t value) override
```

## 備考

* -100%: 最大間隔（棒は完全に分離されています）。
* 0%: 棒は重なりや間隔なしで横に並べられます。
* 100%: 最大重なり（棒は互いに完全に重なります）。このプロパティは読み書き可能な **int8_t**。

次の例は、チャートシリーズ グループの重なりを設定し、結果のチャートをフォームに描画する方法を示しています： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // 重なりを55%に設定

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## 参照

* クラス [ChartSeriesGroup](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)