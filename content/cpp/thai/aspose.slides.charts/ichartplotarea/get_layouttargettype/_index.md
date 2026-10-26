---
title: get_LayoutTargetType()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: หากการจัดวางของพื้นที่พล็อตกำหนดด้วยตนเอง คุณสมบัตินี้ระบุว่าต้องจัดวางพื้นที่พล็อตโดยภายใน (ไม่รวมแกนและป้ายกำกับแกน) หรือโดยภายนอก (รวมแกนและป้ายกำกับแกน) อ่าน LayoutTargetType.
type: docs
weight: 14
url: /th/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() เมธอด

หากการจัดวางของพื้นที่พล็อตกำหนดด้วยตนเอง คุณสมบัตินี้จะระบุว่าจัดวางพื้นที่พล็อตโดยภายใน (ไม่รวมแกนและป้ายกำกับแกน) หรือโดยภายนอก (รวมแกนและป้ายกำกับแกน) อ่าน [LayoutTargetType](../../layouttargettype/).

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
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
* คลาส [IChartPlotArea](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)