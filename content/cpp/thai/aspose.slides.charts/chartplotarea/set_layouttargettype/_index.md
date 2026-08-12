---
title: set_LayoutTargetType()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++ 
description: หากการจัดวางพื้นที่พล็อตกำหนดด้วยตนเอง คุณสมบัตินี้จะระบุว่าจัดวางพื้นที่พล็อตโดยภายใน (ไม่รวมแกนและป้ายแกน) หรือภายนอก (รวมแกนและป้ายแกน) เขียน LayoutTargetType.
type: docs
weight: 183
url: /th/aspose.slides.charts/chartplotarea/set_layouttargettype/
---
## ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) เมธอด


หากการจัดวางพื้นที่พล็อตกำหนดด้วยตนเอง คุณสมบัตินี้จะระบุว่าจัดวางพื้นที่พล็อตโดยภายใน (ไม่รวมแกนและป้ายแกน) หรือภายนอก (รวมแกนและป้ายแกน) เขียน [LayoutTargetType](../../layouttargettype/).

```cpp
void Aspose::Slides::Charts::ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value) override
```

## หมายเหตุ



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

## ดูเพิ่มเติม

* Enum [LayoutTargetType](../../layouttargettype/)
* คลาส [ChartPlotArea](../)
* เนมสเปส [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)