---
title: get_LayoutTargetType()
second_title: Aspose.Slides の C++ API リファレンス
description: プロット領域のレイアウトが手動で定義されている場合、このプロパティはプロット領域を内部（軸および軸ラベルを含まない）でレイアウトするか、外部（軸および軸ラベルを含む）でレイアウトするかを指定します。LayoutTargetType を参照してください。
type: docs
weight: 14
url: /ja/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() メソッド

プロット領域のレイアウトが手動で定義されている場合、このプロパティはプロット領域を内部（軸および軸ラベルを含まない）でレイアウトするか、外部（軸および軸ラベルを含む）でレイアウトするかを指定します。[LayoutTargetType](../../layouttargettype/) を参照してください。

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
```

## 備考

```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 20.0f, 100.0f, 600.0f, 400.0f);

chart->get_PlotArea()->set_X(0.2f);
chart->get_PlotArea()->set_Y(0.2f);
chart->get_PlotArea()->set_Width(0.7f);
chart->get_PlotArea()->set_Height(0.7f);

chart->get_PlotArea()->set_LayoutTargetType(LayoutTargetType::Inner);
// ...
```

## 参照

* Enum [LayoutTargetType](../../layouttargettype/)
* クラス [IChartPlotArea](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)