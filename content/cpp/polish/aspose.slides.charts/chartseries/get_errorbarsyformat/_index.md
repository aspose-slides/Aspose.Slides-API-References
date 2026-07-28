---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides dla C++ Referencja API
description: Reprezentuje ErrorBars serii z kierunkiem Y.
type: docs
weight: 235
url: /pl/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() metoda

Reprezentuje ErrorBars serii z kierunkiem Y.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## Uwagi

ErrorBars z kierunkiem Y są dostępne dla serii typu area, bar, line, scatter i bubble. Dla wszelkich innych typów wykresu ta właściwość zwraca null (w tym wykresy 3D). W przypadku niestandardowych wartości użyj kolekcji DataPoints, aby określić wartość (z właściwością [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Tylko do odczytu [IErrorBarsFormat](../../ierrorbarsformat/). 
## Zobacz również

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IErrorBarsFormat](../../ierrorbarsformat/)
* Klasa [ChartSeries](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)