---
title: get_LayoutTargetType()
second_title: Aspose.Slides C++ API 参考
description: 如果手动定义绘图区域的布局，此属性指定是按内部（不包括坐标轴和坐标轴标签）还是按外部（包括坐标轴和坐标轴标签）进行布局。阅读 LayoutTargetType。
type: docs
weight: 170
url: /zh/aspose.slides.charts/chartplotarea/get_layouttargettype/
---
## ChartPlotArea::get_LayoutTargetType() 方法


如果手动定义了绘图区域的布局，此属性指定是按内部（不包括坐标轴和坐标轴标签）还是按外部（包括坐标轴和坐标轴标签）进行布局。阅读 [LayoutTargetType](../../layouttargettype/)。

```cpp
Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::ChartPlotArea::get_LayoutTargetType() override
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
* 类 [ChartPlotArea](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)