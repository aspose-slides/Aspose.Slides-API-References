---
title: get_LayoutTargetType()
second_title: Aspose.Slides for C++ API 参考
description: 如果手动定义了绘图区的布局，此属性指定是按内部（不包括坐标轴和坐标轴标签）还是按外部（包括坐标轴和坐标轴标签）布局绘图区。阅读 LayoutTargetType。
type: docs
weight: 14
url: /zh/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() 方法


如果手动定义了绘图区的布局，则此属性指定是按内部（不包括坐标轴和坐标轴标签）还是按外部（包括坐标轴和坐标轴标签）布局绘图区。阅读 [LayoutTargetType](../../layouttargettype/)。

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
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

## 另见

* Enum [LayoutTargetType](../../layouttargettype/)
* 类 [IChartPlotArea](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)