---
title: get_LayoutTargetType()
second_title: Справочник API Aspose.Slides для C++
description: Если расположение области построения задаётся вручную, это свойство указывает, следует ли размещать область построения внутри (не включая оси и подписи осей) или снаружи (включая оси и подписи осей). См. LayoutTargetType.
type: docs
weight: 14
url: /ru/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() метод


Если расположение области построения задано вручную, это свойство указывает, следует ли размещать область построения внутри (не включая оси и подписи осей) или снаружи (включая оси и подписи осей). См. [LayoutTargetType](../../layouttargettype/).

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
```

## Примечания



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

## См. также

* Перечисление [LayoutTargetType](../../layouttargettype/)
* Класс [IChartPlotArea](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)