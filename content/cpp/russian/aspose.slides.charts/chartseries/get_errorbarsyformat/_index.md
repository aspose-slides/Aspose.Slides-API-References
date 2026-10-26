---
title: get_ErrorBarsYFormat()
second_title: Справка API Aspose.Slides для C++
description: Представляет ErrorBars серии с направлением Y.
type: docs
weight: 235
url: /ru/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() метод

Представляет ErrorBars серии с направлением Y.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## Примечания

ErrorBars с направлением Y доступны для серий типов area, bar, line, scatter и bubble. Для всех остальных типов диаграмм это свойство возвращает null (включая 3D-диаграммы). В случае пользовательских значений используйте коллекцию DataPoints для указания значения (с свойством [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Только для чтения [IErrorBarsFormat](../../ierrorbarsformat/). 
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IErrorBarsFormat](../../ierrorbarsformat/)
* Класс [ChartSeries](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)