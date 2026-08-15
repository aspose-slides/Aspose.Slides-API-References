---
title: set_LayoutTargetType()
second_title: Aspose.Slides for C++ API 參考
description: 如果手動定義繪圖區域的版面配置，此屬性指定是依其內部（不包括座標軸與座標軸標籤）還是外部（包括座標軸與座標軸標籤）來布局繪圖區域。寫入 LayoutTargetType。
type: docs
weight: 27
url: /zh-hant/aspose.slides.charts/ichartplotarea/set_layouttargettype/
---
## IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) 方法

如果手動定義繪圖區域的版面配置，此屬性指定是依其內部（不包括座標軸與座標軸標籤）還是外部（包括座標軸與座標軸標籤）來布局繪圖區域。寫入 [LayoutTargetType](../../layouttargettype/)。

```cpp
virtual void Aspose::Slides::Charts::IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value)=0
```

## 備註

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

## 參見

* Enum [LayoutTargetType](../../layouttargettype/)
* Class [IChartPlotArea](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)