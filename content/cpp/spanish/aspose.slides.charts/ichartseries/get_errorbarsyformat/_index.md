---
title: get_ErrorBarsYFormat()
second_title: Referencia de API de Aspose.Slides para C++
description: Representa ErrorBars de la serie con dirección Y.
type: docs
weight: 235
url: /es/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() método


Representa ErrorBars de la serie con dirección Y.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## Comentarios


ErrorBars con dirección Y están disponibles para series de tipo area, bar, line, scatter y bubble. Para cualquier otro tipo de gráfico esta propiedad devuelve null (incluidos los gráficos 3D). En caso de valores personalizados, use la colección DataPoints para especificar el valor (con la [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) propiedad). 

Solo lectura [IErrorBarsFormat](../../ierrorbarsformat/). 
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IErrorBarsFormat](../../ierrorbarsformat/)
* Clase [IChartSeries](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)