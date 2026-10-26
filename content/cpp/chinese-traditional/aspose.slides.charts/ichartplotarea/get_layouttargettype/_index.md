---
title: get_LayoutTargetType()
second_title: Aspose.Slides for C++ API 參考
description: 如果圖表區域的版面配置是手動定義的，則此屬性指定是依其內部（不包括坐標軸及坐標軸標籤）還是外部（包括坐標軸及坐標軸標籤）來進行版面配置。請閱讀 LayoutTargetType。
type: docs
weight: 14
url: /zh-hant/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() 方法

如果圖表區域的版面配置是手動定義的，則此屬性指定是依其內部（不包括坐標軸及坐標軸標籤）還是外部（包括坐標軸及坐標軸標籤）來進行版面配置。請參閱 [LayoutTargetType](../../layouttargettype/)。

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
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

## 另請參閱

* 列舉 [LayoutTargetType](../../layouttargettype/)
* 類別 [IChartPlotArea](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)