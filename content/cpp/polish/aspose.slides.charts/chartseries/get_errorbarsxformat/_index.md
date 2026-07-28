---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Reprezentuje ErrorBars serii z kierunkiem X.
type: docs
weight: 222
url: /pl/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() metoda

Reprezentuje ErrorBars serii z kierunkiem X.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## Uwagi

ErrorBars z kierunkiem X są dostępne dla serii typu area, bar, scatter i bubble. Dla wszystkich innych typów wykresu ta właściwość zwraca null (w tym wykresy 3D). W przypadku wartości niestandardowych użyj kolekcji DataPoints, aby określić wartość (z właściwością [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Tylko do odczytu [IErrorBarsFormat](../../ierrorbarsformat/). 
## Zobacz też

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IErrorBarsFormat](../../ierrorbarsformat/)
* Class [ChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)