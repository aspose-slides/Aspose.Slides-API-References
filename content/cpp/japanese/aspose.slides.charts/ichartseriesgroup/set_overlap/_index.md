---
title: set_Overlap()
second_title: Aspose.Slides for C++ APIリファレンス
description: 2-D チャート上でバーと列がどれだけ重なるかをパーセンテージ（-100% から 100%）で指定します。
type: docs
weight: 196
url: /ja/aspose.slides.charts/ichartseriesgroup/set_overlap/
---
## IChartSeriesGroup::set_Overlap(int8_t) メソッド


2-D チャート上でバーと列がどの程度重なり合うかをパーセンテージ（-100% から 100%）で指定します。

```cpp
virtual void Aspose::Slides::Charts::IChartSeriesGroup::set_Overlap(int8_t value)=0
```

## 備考


* -100%: 最大間隔 (バーは完全に分離しています)。
* 0%: バーは重なりも間隔もなく横に配置されます。
* 100%: 最大重なり (バーが互いに完全に重なります)。このプロパティは読み書き **int8_t** です。



以下の例は、チャート シリーズ グループのオーバーラップを設定し、フォーム上に結果のチャートをレンダリングする方法を示しています: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // 重なりを 55% に設定

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```


## 参照

* クラス [IChartSeriesGroup](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)