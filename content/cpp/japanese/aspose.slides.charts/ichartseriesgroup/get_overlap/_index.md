---
title: get_Overlap()
second_title: Aspose.Slides for C++ API リファレンス
description: 2-D チャートにおける棒と列の重なり量をパーセンテージで指定します（-100% から 100% まで）。
type: docs
weight: 183
url: /ja/aspose.slides.charts/ichartseriesgroup/get_overlap/
---
## IChartSeriesGroup::get_Overlap() メソッド


2-D チャートにおいて、棒と列がどれだけ重なるかをパーセンテージで指定します（-100% から 100%）。

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeriesGroup::get_Overlap()=0
```

## 備考


* -100%: 最大間隔（バーは完全に分離されています）。
* 0%: バーは重なりや間隔なしで横に並べられます。
* 100%: 最大重なり（バーは互いに完全に重なります）。このプロパティは read/write **int8_t** です。



次の例は、チャート系列グループの重なりを設定し、フォームに結果のチャートをレンダリングする方法を示しています。 
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