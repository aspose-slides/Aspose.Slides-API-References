---
title: get_LayoutTargetType()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: หากการจัดวางของพื้นที่พล็อตกำหนดด้วยตนเอง คุณสมบัตินี้ระบุว่าจะจัดวางพื้นที่พล็อตโดยใช้ส่วนภายใน (ไม่รวมแกนและป้ายแกน) หรือส่วนภายนอก (รวมแกนและป้ายแกน) อ่าน LayoutTargetType.
type: docs
weight: 170
url: /th/aspose.slides.charts/chartplotarea/get_layouttargettype/
---
## ChartPlotArea::get_LayoutTargetType() เมธอด


หากการจัดวางของพื้นที่พล็อตกำหนดด้วยตนเอง คุณสมบัตินี้ระบุว่าจะจัดวางพื้นที่พล็อตโดยใช้ส่วนภายใน (ไม่รวมแกนและป้ายแกน) หรือส่วนภายนอก (รวมแกนและป้ายแกน) อ่าน [LayoutTargetType](../../layouttargettype/).

```cpp
Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::ChartPlotArea::get_LayoutTargetType() override
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
* เนมสเปซ [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)