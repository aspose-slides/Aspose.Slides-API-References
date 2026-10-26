---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides C++ API referenciája
description: A sorozat Y irányú ErrorBars-át képviseli.
type: docs
weight: 235
url: /hu/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() metódus

Képviseli a sorozat Y irányú ErrorBars-t.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## Megjegyzések

A Y irányú ErrorBars elérhető a area, bar, line, scatter és bubble típusú sorozatokhoz. Más típusú diagramok esetén ez a tulajdonság null értéket ad vissza (beleértve a 3D chartokat). Egyéni értékek esetén használja a DataPoints gyűjteményt az érték megadásához (a [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) tulajdonsággal).

Csak olvasható [IErrorBarsFormat](../../ierrorbarsformat/). 
## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IErrorBarsFormat](../../ierrorbarsformat/)
* Osztály [IChartSeries](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)