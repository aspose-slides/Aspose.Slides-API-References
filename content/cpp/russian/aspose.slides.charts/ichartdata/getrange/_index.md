---
title: GetRange()
second_title: Aspose.Slides для C++ справочник API
description: Получает диапазон данных диаграммы.
type: docs
weight: 170
url: /ru/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() method


Получает диапазон данных диаграммы.

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```


### Возвращаемое значение

Формула диапазона данных ячеек. Например: \"Sheet1!$A$1:$C$4\"
## Примечания




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## См. также

* Класс [String](../../../system/string/)
* Класс [IChartData](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)