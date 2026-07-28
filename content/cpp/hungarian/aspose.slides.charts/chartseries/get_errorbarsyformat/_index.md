---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides C++ API referenciája
description: Ábrázolja a sorozat Y irányú ErrorBars-et.
type: docs
weight: 235
url: /hu/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() metódus

Ábrázolja a sorozat Y irányú ErrorBars-et.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## Megjegyzések

Az Y irányú ErrorBars a következő típusú sorozatoknál érhető el: area, bar, line, scatter és bubble. Más típusú diagramoknál ez a tulajdonság null értéket ad vissza (beleértve a 3D diagramokat is). Egyedi értékek esetén a DataPoints gyűjteményt kell használni az érték megadásához ([IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) tulajdonsággal).

Csak olvasható [IErrorBarsFormat](../../ierrorbarsformat/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IErrorBarsFormat](../../ierrorbarsformat/)
* Osztály [ChartSeries](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)