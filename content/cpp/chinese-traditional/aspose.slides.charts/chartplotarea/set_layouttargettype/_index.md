---
title: set_LayoutTargetType()
second_title: Aspose.Slides C++ API 參考
description: 如果手動定義圖表區域的佈局，此屬性指定是根據其內部（不包括坐標軸和坐標軸標籤）還是外部（包括坐標軸和坐標軸標籤）來佈局圖表區域。寫入 LayoutTargetType。
type: docs
weight: 183
url: /zh-hant/aspose.slides.charts/chartplotarea/set_layouttargettype/
---
## ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) 方法

如果手動定義圖表區域的佈局，則此屬性指定是根據其內部（不包括坐標軸和坐標軸標籤）還是外部（包括坐標軸和坐標軸標籤）來佈局圖表區域。寫入 [LayoutTargetType](../../layouttargettype/)。

```cpp
void Aspose::Slides::Charts::ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value) override
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

## 另見

* 列舉 [LayoutTargetType](../../layouttargettype/)
* 類別 [ChartPlotArea](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)