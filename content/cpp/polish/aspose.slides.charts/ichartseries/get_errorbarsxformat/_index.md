---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides dla API C++
description: Reprezentuje ErrorBars serii w kierunku X.
type: docs
weight: 222
url: /pl/aspose.slides.charts/ichartseries/get_errorbarsxformat/
---
## IChartSeries::get_ErrorBarsXFormat() metoda


Reprezentuje ErrorBars serii w kierunku X.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsXFormat()=0
```

## Uwagi


ErrorBars w kierunku X są dostępne dla serii typu area, bar, scatter i bubble. Dla wszystkich innych typów wykresów ta właściwość zwraca null (w tym wykresy 3D). W przypadku wartości niestandardowych użyj kolekcji DataPoints, aby określić wartość (z [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) właściwością). 

Tylko do odczytu [IErrorBarsFormat](../../ierrorbarsformat/). 
## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IErrorBarsFormat](../../ierrorbarsformat/)
* Klasa [IChartSeries](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)