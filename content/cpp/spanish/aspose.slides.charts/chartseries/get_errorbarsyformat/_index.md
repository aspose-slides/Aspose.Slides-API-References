---
title: get_ErrorBarsYFormat()
second_title: Referencia de API de Aspose.Slides para C++
description: Representa ErrorBars de series con dirección Y.
type: docs
weight: 235
url: /es/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() método

Representa ErrorBars de la serie con dirección Y.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## Observaciones

ErrorBars con dirección Y están disponibles para series de tipo area, bar, line, scatter y bubble. Para cualquier otro tipo de gráfico esta propiedad devuelve null (incluidos los gráficos 3D). En caso de valores personalizados, use la colección DataPoints para especificar el valor (con la propiedad [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Solo lectura [IErrorBarsFormat](../../ierrorbarsformat/). 
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IErrorBarsFormat](../../ierrorbarsformat/)
* Clase [ChartSeries](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)