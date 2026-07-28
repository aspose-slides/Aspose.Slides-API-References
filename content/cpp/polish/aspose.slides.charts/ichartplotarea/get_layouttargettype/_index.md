---
title: get_LayoutTargetType()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Jeśli układ obszaru wykresu jest definiowany ręcznie, ta właściwość określa, czy układać obszar wykresu od wewnątrz (bez osi i etykiet osi) lub od zewnątrz (z uwzględnieniem osi i etykiet osi). Przeczytaj LayoutTargetType.
type: docs
weight: 14
url: /pl/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() metoda


Jeśli układ obszaru wykresu jest definiowany ręcznie, to własność określa, czy układać obszar wykresu od wewnątrz (bez osi i etykiet osi) lub od zewnątrz (z uwzględnieniem osi i etykiet osi). Przeczytaj [LayoutTargetType](../../layouttargettype/).

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
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

* Enum [LayoutTargetType](../../layouttargettype/)
* Klasa [IChartPlotArea](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)