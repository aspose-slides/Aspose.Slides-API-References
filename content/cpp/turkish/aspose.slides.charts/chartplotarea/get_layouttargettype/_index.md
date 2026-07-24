---
title: get_LayoutTargetType()
second_title: Aspose.Slides C++ API Referansı
description: Grafik alanının düzeni manuel olarak tanımlanmışsa, bu özellik grafik alanını iç kısmına (eksen ve eksen etiketleri hariç) veya dış kısmına (eksen ve eksen etiketleri dahil) düzenleyip düzenlemeyeceğini belirtir. Oku LayoutTargetType.
type: docs
weight: 170
url: /tr/aspose.slides.charts/chartplotarea/get_layouttargettype/
---
## ChartPlotArea::get_LayoutTargetType() yöntemi

Eğer grafik alanının düzeni manuel olarak tanımlanmışsa, bu özellik grafik alanını iç kısmına (eksen ve eksen etiketleri hariç) veya dış kısmına (eksen ve eksen etiketleri dahil) düzenleyip düzenlemeyeceğini belirler. Oku [LayoutTargetType](../../layouttargettype/).

```cpp
Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::ChartPlotArea::get_LayoutTargetType() override
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
* Sınıf [ChartPlotArea](../)
* Ad Alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)