---
title: set_LayoutTargetType()
second_title: Aspose.Slides for C++ API Referansı
description: Eğer grafik alanının yerleşimi manuel olarak tanımlanmışsa, bu özellik grafik alanını iç kısmına (eksen ve eksen etiketleri hariç) veya dış kısmına (eksen ve eksen etiketleri dahil) yerleştirip yerleştirilmeyeceğini belirtir. LayoutTargetType yazın.
type: docs
weight: 183
url: /tr/aspose.slides.charts/chartplotarea/set_layouttargettype/
---
## ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) yöntemi


Eğer çizim alanının yerleşimi manuel olarak tanımlanmışsa, bu özellik çizim alanını iç kısmına (eksen ve eksen etiketleri hariç) veya dış kısmına (eksen ve eksen etiketleri dahil) yerleştirip yerleştirilmeyeceğini belirtir. [LayoutTargetType](../../layouttargettype/) yazın.

```cpp
void Aspose::Slides::Charts::ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value) override
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

## Ayrıca bakınız

* Enum [LayoutTargetType](../../layouttargettype/)
* Sınıf [ChartPlotArea](../)
* İsim alanı [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)