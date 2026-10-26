---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides for C++ API referenciája
description: Az X irányú sorozat ErrorBars értékeit képviseli.
type: docs
weight: 222
url: /hu/aspose.slides.charts/ichartseries/get_errorbarsxformat/
---
## IChartSeries::get_ErrorBarsXFormat() metódus


Az X irányú sorozat ErrorBars értékeit képviseli.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsXFormat()=0
```

## Megjegyzés


Az X irányú ErrorBars elérhető area, bar, scatter és bubble típusú sorozatok számára. Bármely más diagramtípus esetén ez a tulajdonság null értéket ad vissza (beleértve a 3D diagramokat is). Egyéni értékek esetén a DataPoints gyűjteményt kell használni az érték meghatározásához ([IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) tulajdonsággal). 

Csak olvasható [IErrorBarsFormat](../../ierrorbarsformat/). 
## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IErrorBarsFormat](../../ierrorbarsformat/)
* Osztály [IChartSeries](../)
* Névterület [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)