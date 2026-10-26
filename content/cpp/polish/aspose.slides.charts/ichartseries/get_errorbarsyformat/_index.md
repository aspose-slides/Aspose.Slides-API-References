---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides dla referencji API C++
description: Reprezentuje ErrorBars serii z kierunkiem Y.
type: docs
weight: 235
url: /pl/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() metoda

Reprezentuje ErrorBars serii z kierunkiem Y.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## Uwagi

ErrorBars z kierunkiem Y są dostępne dla serii typu area, bar, line, scatter i bubble. Dla innych typów wykresów ta właściwość zwraca null (w tym wykresy 3D). W przypadku wartości niestandardowych użyj kolekcji DataPoints, aby określić wartość (z właściwością [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Tylko do odczytu [IErrorBarsFormat](../../ierrorbarsformat/). 
## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IErrorBarsFormat](../../ierrorbarsformat/)
* Klasa [IChartSeries](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)