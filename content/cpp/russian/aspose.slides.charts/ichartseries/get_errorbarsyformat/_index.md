---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides для справочника API C++
description: Представляет ErrorBars серии с направлением Y.
type: docs
weight: 235
url: /ru/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() метод

Представляет ErrorBars серии с направлением Y.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## Примечания

ErrorBars с направлением Y доступны для серий типов area, bar, line, scatter и bubble. Для всех остальных типов диаграмм это свойство возвращает null (включая 3D диаграммы). В случае пользовательских значений используйте коллекцию DataPoints для указания значения (свойство [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Только для чтения [IErrorBarsFormat](../../ierrorbarsformat/). 
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IErrorBarsFormat](../../ierrorbarsformat/)
* Класс [IChartSeries](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)