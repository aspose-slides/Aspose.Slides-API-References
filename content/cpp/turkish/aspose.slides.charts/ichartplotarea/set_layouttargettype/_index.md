---
title: set_LayoutTargetType()
second_title: Aspose.Slides için C++ API Referansı
description: Çizim alanının düzeni manuel olarak tanımlanmışsa, bu özellik çizim alanını iç kısmına (eksen ve eksen etiketleri dahil olmadan) ya da dış kısmına (eksen ve eksen etiketleri dahil) göre düzenleyip düzenlemeyeceğini belirtir. LayoutTargetType değerini yazın.
type: docs
weight: 27
url: /tr/aspose.slides.charts/ichartplotarea/set_layouttargettype/
---
## IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) yöntemi

Eğer çizim alanının düzeni manuel olarak tanımlanmışsa, bu özellik çizim alanını iç kısmına (eksen ve eksen etiketleri dahil olmadan) ya da dış kısmına (eksen ve eksen etiketleri dahil) göre düzenleyip düzenlemeyeceğini belirtir. Yaz [LayoutTargetType](../../layouttargettype/).

```cpp
virtual void Aspose::Slides::Charts::IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value)=0
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

## Diğer

* Enum [LayoutTargetType](../../layouttargettype/)
* Sınıf [IChartPlotArea](../)
* AdAlanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)