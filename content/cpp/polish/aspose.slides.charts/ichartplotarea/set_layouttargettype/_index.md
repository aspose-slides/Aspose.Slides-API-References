---
title: set_LayoutTargetType()
second_title: Aspose.Slides dla interfejsu API C++
description: Jeśli układ obszaru wykresu jest definiowany ręcznie, ta właściwość określa, czy układać obszar wykresu od wewnątrz (nie uwzględniając osi i etykiet osi) czy od zewnątrz (uwzględniając oś i etykiety osi). Zapisz LayoutTargetType.
type: docs
weight: 27
url: /pl/aspose.slides.charts/ichartplotarea/set_layouttargettype/
---
## IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) metoda


Jeśli układ obszaru wykresu jest definiowany ręcznie, to ta właściwość określa, czy układać obszar wykresu wewnątrz (nie uwzględniając osi i etykiet osi) czy na zewnątrz (uwzględniając oś i etykiety osi). Zapisz [LayoutTargetType](../../layouttargettype/).

```cpp
virtual void Aspose::Slides::Charts::IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value)=0
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
* Klasa [IChartPlotArea](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)