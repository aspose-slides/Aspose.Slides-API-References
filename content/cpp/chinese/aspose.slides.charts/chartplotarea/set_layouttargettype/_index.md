---
title: set_LayoutTargetType()
second_title: Aspose.Slides C++ API 参考
description: 如果手动定义了绘图区域的布局，此属性指定是按内部（不包括轴和轴标签）布局绘图区域，还是按外部（包括轴和轴标签）布局。写入 LayoutTargetType.
type: docs
weight: 183
url: /zh/aspose.slides.charts/chartplotarea/set_layouttargettype/
---
## ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) 方法

如果手动定义了绘图区域的布局，此属性指定是按内部（不包括轴和轴标签）布局绘图区域，还是按外部（包括轴和轴标签）布局。写入 [LayoutTargetType](../../layouttargettype/)。

```cpp
void Aspose::Slides::Charts::ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value) override
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

* 枚举 [LayoutTargetType](../../layouttargettype/)
* 类 [ChartPlotArea](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)