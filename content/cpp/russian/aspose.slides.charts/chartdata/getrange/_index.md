---
title: GetRange()
second_title: Справочник API Aspose.Slides для C++
description: Получает диапазон данных диаграммы.
type: docs
weight: 157
url: /ru/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() метод


Получает диапазон данных диаграммы.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```


### Возвращаемое значение

Формула диапазона данных ячеек. Например: \"Sheet1!$A$1:$C$4\"
## Примечания




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## См. также

* Класс [String](../../../system/string/)
* Класс [ChartData](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)