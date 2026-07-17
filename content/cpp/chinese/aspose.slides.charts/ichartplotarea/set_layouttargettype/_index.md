---
title: set_LayoutTargetType()
second_title: Aspose.Slides C++ API 参考
description: 如果绘图区域的布局是手动定义的，则此属性指定是按内部布局（不包括坐标轴和坐标轴标签）还是按外部布局（包括坐标轴和坐标轴标签）。写入 LayoutTargetType.
type: docs
weight: 27
url: /zh/aspose.slides.charts/ichartplotarea/set_layouttargettype/
---
## IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) 方法


如果手动定义了绘图区域的布局，则此属性指定是按内部布局（不包括坐标轴和坐标轴标签）还是按外部布局（包括坐标轴和坐标轴标签）。写入 [LayoutTargetType](../../layouttargettype/).

```cpp
virtual void Aspose::Slides::Charts::IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value)=0
```

## 备注



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

## 另请参阅

* 枚举 [LayoutTargetType](../../layouttargettype/)
* 类 [IChartPlotArea](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)