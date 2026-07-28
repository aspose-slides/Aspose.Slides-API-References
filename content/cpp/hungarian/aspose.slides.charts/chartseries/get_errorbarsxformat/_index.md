---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides C++ API-referencia
description: Az X irányú sorozat ErrorBars-ét képviseli.
type: docs
weight: 222
url: /hu/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() metódus

Az X irányú sorozat ErrorBars-ét képviseli.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## Megjegyzések

Az X irányú ErrorBars elérhetők az area, bar, scatter és bubble típusú sorozatokhoz. Bármely más típusú diagram esetén ez a tulajdonság null értéket ad vissza (beleértve a 3D diagramokat is). Egyedi értékek esetén a DataPoints gyűjteményt kell használni az érték megadásához ([IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) tulajdonsággal).

Csak olvasható [IErrorBarsFormat](../../ierrorbarsformat/). 

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IErrorBarsFormat](../../ierrorbarsformat/)
* Osztály [ChartSeries](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)