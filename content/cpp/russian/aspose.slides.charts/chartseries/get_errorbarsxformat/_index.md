---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides для C++ справочник API
description: Представляет ErrorBars серии с направлением X.
type: docs
weight: 222
url: /ru/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() метод

Представляет ErrorBars серии с направлением X.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## Примечания

ErrorBars с направлением X доступны для серий типа area, bar, scatter и bubble. Для всех остальных типов диаграмм это свойство возвращает null (включая 3D-диаграммы). В случае пользовательских значений используйте коллекцию DataPoints, чтобы указать значение (со свойством [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Только для чтения [IErrorBarsFormat](../../ierrorbarsformat/). 

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IErrorBarsFormat](../../ierrorbarsformat/)
* Класс [ChartSeries](../)
* Пространство имен [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)