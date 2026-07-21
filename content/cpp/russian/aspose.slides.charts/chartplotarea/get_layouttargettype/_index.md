---
title: get_LayoutTargetType()
second_title: Aspose.Slides для C++ справка API
description: Если расположение области построения задано вручную, это свойство указывает, следует ли размещать область построения по её внутренней части (не включая оси и подписи осей) или по внешней части (включая оси и подписи осей). Читайте LayoutTargetType.
type: docs
weight: 170
url: /ru/aspose.slides.charts/chartplotarea/get_layouttargettype/
---
## ChartPlotArea::get_LayoutTargetType() метод

Если расположение области построения задано вручную, это свойство указывает, следует ли размещать область построения по её внутренней части (не включая оси и подписи осей) или по внешней части (включая оси и подписи осей). Читайте [LayoutTargetType](../../layouttargettype/).

```cpp
Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::ChartPlotArea::get_LayoutTargetType() override
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
* Класс [ChartPlotArea](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)