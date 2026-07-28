---
title: get_LayoutTargetType()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Jeśli układ obszaru wykresu jest definiowany ręcznie, ta właściwość określa, czy układać obszar wykresu wewnątrz (nie obejmując osi i etykiet osi) czy na zewnątrz (obejmując oś i etykiety osi). Przeczytaj LayoutTargetType.
type: docs
weight: 170
url: /pl/aspose.slides.charts/chartplotarea/get_layouttargettype/
---
## ChartPlotArea::get_LayoutTargetType() metoda

Jeśli układ obszaru wykresu jest definiowany ręcznie, ta właściwość określa, czy układać obszar wykresu wewnątrz (nie obejmując osi i etykiet osi) czy na zewnątrz (obejmując oś i etykiety osi). Przeczytaj [LayoutTargetType](../../layouttargettype/).

```cpp
Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::ChartPlotArea::get_LayoutTargetType() override
```

## Uwagi

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

## Zobacz także

* Wyliczenie [LayoutTargetType](../../layouttargettype/)
* Klasa [ChartPlotArea](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)