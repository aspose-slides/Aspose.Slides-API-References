---
title: get_LayoutTargetType()
second_title: Aspose.Slides for C++ API Referansı
description: Grafik alanının yerleşimi manuel olarak tanımlanmışsa bu özellik grafik alanını iç kısmına (eksen ve eksen etiketleri hariç) ya da dış kısmına (eksen ve eksen etiketleri dahil) yerleştirip yerleştirmeyeceğini belirtir. LayoutTargetType'ı okuyun.
type: docs
weight: 14
url: /tr/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() metot


Grafik alanının yerleşimi manuel olarak tanımlanmışsa bu özellik grafik alanını iç kısmına (eksen ve eksen etiketleri hariç) ya da dış kısmına (eksen ve eksen etiketleri dahil) yerleştirip yerleştirmeyeceğini belirtir. Okuyun [LayoutTargetType](../../layouttargettype/).

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
```

## Açıklamalar



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

## Ayrıca Bakınız

* Enum [LayoutTargetType](../../layouttargettype/)
* Sınıf [IChartPlotArea](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)