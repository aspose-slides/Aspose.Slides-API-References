---
title: set_LayoutTargetType()
second_title: C++ 用 Aspose.Slides API リファレンス
description: プロット領域のレイアウトが手動で定義されている場合、このプロパティは、軸と軸ラベルを除く内部でレイアウトするか、軸と軸ラベルを含む外部でレイアウトするかを指定します。LayoutTargetType を書き込みます。
type: docs
weight: 183
url: /ja/aspose.slides.charts/chartplotarea/set_layouttargettype/
---
## ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) method


プロット領域のレイアウトが手動で定義されている場合、このプロパティは、プロット領域を内部（軸と軸ラベルを除く）でレイアウトするか、外部（軸と軸ラベルを含む）でレイアウトするかを指定します。[LayoutTargetType](../../layouttargettype/)を書き込みます。

```cpp
void Aspose::Slides::Charts::ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value) override
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
* Class [ChartPlotArea](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)