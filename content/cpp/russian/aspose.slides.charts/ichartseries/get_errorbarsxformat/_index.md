---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides для C++ справочника API
description: Представляет ErrorBars серии с направлением X.
type: docs
weight: 222
url: /ru/aspose.slides.charts/ichartseries/get_errorbarsxformat/
---
## IChartSeries::get_ErrorBarsXFormat() method

Представляет ErrorBars серии с направлением X.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsXFormat()=0
```

## Примечания

ErrorBars с направлением X доступны для серий типа area, bar, scatter и bubble. Для всех остальных типов диаграмм это свойство возвращает null (включая 3D-диаграммы). В случае пользовательских значений используйте коллекцию DataPoints для указания значения (с свойством [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Только чтение [IErrorBarsFormat](../../ierrorbarsformat/). 
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IErrorBarsFormat](../../ierrorbarsformat/)
* Класс [IChartSeries](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)