---
title: set_LayoutTargetType()
second_title: Aspose.Slides for C++ APIリファレンス
description: プロット領域のレイアウトが手動で定義されている場合、このプロパティは領域を内部（軸および軸ラベルを除く）でレイアウトするか、外部（軸および軸ラベルを含む）でレイアウトするかを指定します。LayoutTargetTypeを書きます。
type: docs
weight: 27
url: /ja/aspose.slides.charts/ichartplotarea/set_layouttargettype/
---
## IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) メソッド

プロット領域のレイアウトが手動で定義されている場合、このプロパティはプロット領域を内部（軸および軸ラベルを除く）でレイアウトするか、外部（軸および軸ラベルを含む）でレイアウトするかを指定します。[LayoutTargetType](../../layouttargettype/)を書きます。

```cpp
virtual void Aspose::Slides::Charts::IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value)=0
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
* Library [Aspose.Slides](../../../)