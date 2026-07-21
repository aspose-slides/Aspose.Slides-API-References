---
title: set_LayoutTargetType()
second_title: Aspose.Slides для C++: справочник API
description: Если расположение области построения определено вручную, это свойство указывает, следует ли размещать область построения внутри (не включая оси и подписи осей) или снаружи (включая оси и подписи осей). Запишите LayoutTargetType.
type: docs
weight: 27
url: /ru/aspose.slides.charts/ichartplotarea/set_layouttargettype/
---
## IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) метод


Если расположение области построения определено вручную, это свойство указывает, следует ли размещать область построения внутри (не включая оси и подписи осей) или снаружи (включая оси и подписи осей).

Запишите [LayoutTargetType](../../layouttargettype/).

```cpp
virtual void Aspose::Slides::Charts::IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value)=0
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

## Смотрите также

* Перечисление [LayoutTargetType](../../layouttargettype/)
* Класс [IChartPlotArea](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)