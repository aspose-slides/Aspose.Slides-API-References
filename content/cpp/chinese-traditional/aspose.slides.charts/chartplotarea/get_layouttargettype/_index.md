---
title: get_LayoutTargetType()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 如果繪圖區的版面配置是手動定義的，則此屬性指定是以繪圖區的內部（不包括軸和軸標籤）還是外部（包括軸和軸標籤）進行版面配置。閱讀 LayoutTargetType。
type: docs
weight: 170
url: /zh-hant/aspose.slides.charts/chartplotarea/get_layouttargettype/
---
## ChartPlotArea::get_LayoutTargetType() 方法

如果繪圖區的版面配置是手動定義的，則此屬性指定是以繪圖區的內部（不包括軸和軸標籤）還是外部（包括軸和軸標籤）進行版面配置。閱讀 [LayoutTargetType](../../layouttargettype/)。

```cpp
Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::ChartPlotArea::get_LayoutTargetType() override
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

* Enum [LayoutTargetType](../../layouttargettype/)
* 類別 [ChartPlotArea](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)